# 本文是对Linux下的触摸驱动进行总结，会列出详细的源码，以便读者可以直接使用。

## 一、何为触摸

目前信息化的时代，各式各样带显示屏的电子设备基本都有触摸功能，触摸已经成为我们和设备交互的重要手段。
本文主要以电容触摸屏为例，大概讲解下触摸驱动的框架，就当是一份笔记吧。
