# Landfall

A [VV](https://github.com/bradp/vv/) blueprint for a preconfigured WordPress Multisite installation with which to demo [Buoy](https://betterangels.github.io/buoy/).

First, install [VirtualBox](https://www.virtualbox.org/wiki/Downloads), [Vagrant](https://www.vagrantup.com/downloads.html), [VVV](https://github.com/Varying-Vagrant-Vagrants/VVV#the-first-vagrant-up), and [VV](https://github.com/bradp/vv#installation) if you have not already done so.

Then download this config file and use it as your VV blueprint:

```sh
git clone https://github.com/meitar/landfall.git
cp landfall/vv-landfall-blueprint.json vagrant-local/vv-blueprints.json
vv --blueprint vvv-landfall
```

And you're done. :)
