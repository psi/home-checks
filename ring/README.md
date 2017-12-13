## check_ring

### Installation & configuration

```shell
# Install dependencies
$ pip install -r requirements.txt

# Set credentials
$ export RING_EMAIL=<YOUR RING.COM EMAIL ADDRESS>
$ export RING_PASSWORD=<YOUR RING.COM PASSWORD>
```

### Usage

```shell
# Check battery life of your doorbell
$ ./check_ring -t doorbell -a battery

# Check WiFi signal strength of your doorbell
$ ./check_ring -t doorbell -a wifi

# Check WiFi signal strength of your Chime
$ ./check_ring -t chime -a wifi
```
