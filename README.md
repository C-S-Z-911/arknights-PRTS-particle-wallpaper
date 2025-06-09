# 基于明日方舟官网制作的动态粒子壁纸

[![Wallpaper Engine](https://img.shields.io/badge/Wallpaper%20Engine-✓-green?logo=steam)](https://store.steampowered.com/app/431960/Wallpaper_Engine/)
[![PRTS Style](https://img.shields.io/badge/Style-PRTS-blueviolet)](https://ak.hypergryph.com/)

> steam创意工坊:https://steamcommunity.com/sharedfiles/filedetails/?id=3486243270

![预览图](preview.jpg)

## [功能特性]
- **更改/自定义粒子图案**
- **更改光标外边框**
- **⚠️**: 由于wallpaper与代码的原因,只能通过切换壁纸才能应用对壁纸的设置

## [json格式]
```
// 粒子配置
{
  "count": 4237,  //粒子数量,上线为10000
  "size": {
    "width": 490,  //宽(x)
    "height": 198  //高(h)
  },
  "points": [  //粒子生成位置及颜色(rgba)
    [147,6,"#f2f2f25f"],
    [150,6,"#f2f2f25f"],
    ...
  ]
}
```
- **图片转json脚本**: https://github.com/C-S-Z-911/Images-to-JSON-particle/settings
- **注意事项**
  - 粒子数量超过10000时预览可能不完整
  - 颜色必须必为十六进制RGBA格式
  - json粒子 宽/高 最好控制在 512*512 左右以便拥有较好的显示效果

## 关于
- **源码**: https://steamcommunity.com/sharedfiles/filedetails/?id=2447798562
