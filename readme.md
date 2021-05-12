### RmlUi- 基于HTML/CSS的C++用户界面库

RmlUi是基于HTML和CSS标准的C++界面库，当前版本4.0

多平台支持，MIT开源协议

RmlUi支持大多数CSS2，并具有一些CSS3功能，支持常见的HTML元素

[css支持列表](https://mikke89.github.io/RmlUiDoc/pages/rcss/property_index.html)

[HTML元素支持列表](https://mikke89.github.io/RmlUiDoc/pages/rml/element_index.html)

![BinFile/DemoSample.jpg](BinFile/DemoSample.jpg)

##### 编译依赖

[FreeType](https://www.freetype.org/)



#### window下cmake编译说明

编译好的例子 [BinFile](./BinFile)

游戏invaders例子 [BinFile/invaders.exe](./BinFile/invaders.exe)

##### 宏定义

勾选 BUILD_SAMPLES，生成例子工程

去除 NO_FONT_INTERFACE_DEFAULT的宏定义编译，否者例子初始化失败，直接退出。

取消勾选BUILD_SHARED_LIBS，生成RmlCore.lib，RmlDebugger.lib静态库


##### 教程例子 tutorial_xxxxx

只依赖RmlCore.dll和RmlDebugger.dll。


##### 特殊例子 sdl2 

依赖 SDL2-2.0.14，SDL2_image-2.0.5-VC，glew-2.2.0-win32

##### 特殊例子 sfml2  

依赖SFML-2.5.1-vs2017-x86,默认使用动态编译。

##### 其它例子

只依赖RmlCore.dll和RmlDebugger.dll。