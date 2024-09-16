# weewx-freebsd-rc.d

This is an `rc.d` file for FreeBSD that runs weewx as a service.

## Usage

1. Copy `weewx` to `/usr/local/etc/rc.d`, creating the directory if necessary.
1. Enable the service with `sysrc weewx_enable="YES"`.
1. Configure any necessary variables in `/etc/rc.conf`. For example, set the `weewx` configuration file by adding `weewx_config_file=/path/to/config` to `/etc/rc.conf`.
1. Start the `weewx` service with `service weewx start`.
