# spacedust-texture-tools

tools for modifying textures for [spacedust](http://www.spacedust.info)

**Installation**

1. git clone git@github.com:mjwhitt/spacedust-texture-tools.git
2. cd spacedust-texture-tools/
3. bundle install --path vendor/

**Examples**

![original](examples/water.png)

> ./bin/extract-value examples/water.png examples/water-value.png

![value](examples/water-value.png)

>  ./bin/apply-hue 300 50 examples/water-value.png examples/water-hue-300.png

![hue 300](examples/water-hue-300.png)

>  ./bin/apply-hue 100 50 examples/water-value.png examples/water-hue-100.png

![hue 100](examples/water-hue-100.png)
