# spacedust-texture-tools

tools for modifying textures for [spacedust](http://www.spacedust.info)

**Installation**

1. git clone git@github.com:mjwhitt/spacedust-texture-tools.git
2. cd spacedust-texture-tools/
3. bundle install --path vendor/

**Examples**

![original](examples/water.png)

> ./bin/extract-lightness examples/water.png examples/water-lightness.png

![lightness](examples/water-lightness.png)

>  ./bin/apply-hue 300 39 examples/water-lightness.png examples/water-hue-300.png

![hue 300](examples/water-hue-300.png)

>  ./bin/apply-hue 100 39 examples/water-lightness.png examples/water-hue-100.png

![hue 100](examples/water-hue-100.png)

**See Also**

* [Dynamic Colors](http://www.spacedust.info/2015/10/dynamic-colors/)
