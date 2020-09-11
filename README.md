# EarthWallpaper
shell版地球背景,依赖 ImageMagick

# 安装
ubuntu为例
首先安装 ImageMagick,安装过的跳过
```
sudo apt-get install imagemagick
```

然后安装程序
```
sudo git clone https://github.com/ghostry/EarthWallpaper.git /opt/EarthWallpaper
ln -s /opt/EarthWallpaper/earthWallpaper.desktop ~/.config/autostart
```

# 卫星选择
编辑 earthWallpaper 中的 第6行 using="himawari8"
目前有三个卫星可选

## himawari8[向日葵8号]
using="himawari8"

![向日葵8号](himawari8.jpg)

## fy4a[风云4号]
using="fy4a"

![风云4号](fy4a.jpg)

## goes16
using="goes16"

![GOES16](goes16.jpg)

## goes17
using="goes17"

![GOES17](goes17.jpg)
