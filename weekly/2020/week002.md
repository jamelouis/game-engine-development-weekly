# 周报 第2期

## 文章

1. [GBuffer helper - Packing integer and float](https://seblagarde.wordpress.com/2018/09/02/gbuffer-helper-packing-integer-and-float-together/)
   
    GBuffer Layout是Defered Rendering重要组成。Layout一般都需要将int和float的数值编码到GBuffer对应LDR纹理中。本篇博文主要论述了如何编码int和float数值的过程。

2. [PBR - github](https://github.com/Nadrin/PBR) (*code*)

    Nadrin用不同的图形API(OpenGL, OpenGLES, Vulkan, Dx11, DX12)实现PBR和IBL算法。

3. [Physically Based Rendering in Filament](https://google.github.io/filament/Filament.md.html) (*code*)

    Filament是实时的基于物理渲染引擎，支持Android,iOS,Linux,macOS, Windows, 和WebGL。该博文主要阐述了PBR公式和背后的理论，并且介绍了特定算法的选择缘由。
    
    [Filement - github](https://github.com/google/filament)

4. [px_render.h rationale](https://pplux.github.io/why_px_render.html) (*code*)

    px_render一个单独的c++头文件，实现了底层的渲染库。

    [px_render.h - github](https://github.com/pplux/px/blob/master/px_render.h)

5. [cross platform shaders](https://aras-p.info/blog/2014/03/28/cross-platform-shaders-in-2014/)
  
    本博文介绍如何在引擎开发中编写跨平台的shader？利用宏，或者以hlsl和glsl为backend来重新定义一个shader语言，或者字节码间的转换，或者选择一个shader语言，利用第三方工具（HLSL Cross Compiler - UE4， hlsl2glslfork - Unity）进行不同着色语言的转换。


6. [Visualizing floating point precision loss](https://www.shadertoy.com/view/4tVyDK)

    可视化float数值类型的精度缺失。

7. [rasterization vs ray tracing vs path tracing](https://medium.com/@junyingw/future-of-gaming-rasterization-vs-ray-tracing-vs-path-tracing-32b334510f1f)

    栅格化 vs 光线追踪 vs 路径追踪

8. [inside shipping on ios](http://loopit.dk/inside_shipping_on_ios.pdf)

    该pdf主要介绍如何将独立游戏inside移植到ios平台的过程。


9. [GPU font rendering](http://terathon.com/font_rendering_sota_lengyel.pdf)

    介绍了目前基于GPU的字体渲染的技术水平。

10. [post-processing effects on mobile: optimization and alternatives](https://community.arm.com/developer/tools-software/graphics/b/blog/posts/post-processing-effects-on-mobile-optimization-and-alternatives)
    
    手机端GPU一般采用基于tile的渲染体系。基于这个基本点，forward rendering比deferred rendering更适合作为移动端的渲染技术方案。文章中详细剖析了Bloom在手游Nordeus's Spellsouls的优化过程和其他不基于后期处理技术的bloom效果方案。


## 教程

1. [immersivemath](http://immersivemath.com/ila/learnmore.html)

    一个可交互式插图的关于线性代数的网站。

2. [Moving Mobile Graphics](https://community.arm.com/developer/tools-software/graphics/b/blog/posts/moving-mobile-graphics)

    Siggraph的课程，旨在介绍移动端图形开发的当前现状。


## 资料

1. [Readings(shader, maths, 3D)](https://shadertoyunofficial.wordpress.com/2018/04/16/readings-shaders-maths-3d/)

    给初学者关于shader， 数学和3D的资料。

2. [Compilation of 100+ 3D graphics academic](https://gregstoll.com/~gregstoll/floattohex/)

    Hugo Viala收集的关于3Dgraphics学术论文。以主题归类，如全局光照，阴影，渲染等等。


## 工具

1. [introducing shader playground](http://timjones.io/blog/archive/2018/05/19/introducing-shader-playground)

    在线的着色器编译器。

2.  [idb - github](https://fbidb.io/)

    idb, facebook开源的一个终端工具。idb提供了类似于android平台的adb的功能。

3. [dxbc reader - github](https://github.com/luxuia/dxbc_reader)

    可以把hlsl字节码逆向到hlsl文本的lua脚本。