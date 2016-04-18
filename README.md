# Landfall

A [VV](https://github.com/bradp/vv/) blueprint for a preconfigured WordPress Multisite installation with which to demo [Buoy](https://betterangels.github.io/buoy/).

Until certain pull requests are merged, you need to use my personal fork of VV that implements several additional blueprint features.

First, get VV and this config:

```sh
mkdir ~/bin && cd ~/bin
git clone -b meitar-blueprints --single-branch https://github.com/meitar/vv.git
git clone https://github.com/meitar/landfall.git
```

Then copy the `vv-landfall-blueprint.json` file to your VVV root directory as `vv-blueprints.json`.

Now you just `vv create --blueprint vvv-landfall` and you're done. :)
