# 周报 第3期

## 文章

1. [fx-gltf - github](https://github.com/jessey-git/fx-gltf)
    
    对glTF2.0的序列化和反序列化c++14/17的库。

2. [3d file format - last-mile vs interchange](http://nickporcino.com/posts/last_mile_interchange.html)
    
    从文件格式的意图讨论了3d文件格式的分类: last_mile和interchange。涉及到了gltf, fbx, alembic, usd, collada, antiques(obj,ply,stl,etc)等格式。

3. [gpu info](https://www.gpuinfo.org/)
   
   一个在线的GPU硬件数据库，为图形开发者提供某个特定驱动或者GPU支持了哪些特征。目前有OpenGL, Vulkan, OpenGLES。

4. [fg - github](https://github.com/acdemiralp/fg)
   
    > Rendering abstraction which describes a frame as a directed acyclic graph of render tasks and resources.

5. [Tools and Techniques for debugging and optimization](https://docs.google.com/presentation/d/1LQUMIld4SGoQVthnhT1scoA3k4Sg0as14G4NeSiSgFU/edit#slide=id.p)
  
  调试和优化图形的工具箱和技巧。常见的图形问题，将调试信息编码的rgb输出，利用类似renderdoc的工具来进行帧调试和shader调试。通过使用GPU PerfStudio, RTTV, PIX工具来做性能分析瓶颈是在CPU端还是GPU端。

6. [reverse z](https://thxforthefish.com/posts/reverse_z/)
    
    采用reverse-z技术来改善深度纹理浮点精度比较的问题

7. [ieee754 visualization](http://bartaz.github.io/ieee754-visualization/)
   
   在线的double可视化。

8. [unreal engine rendering](https://medium.com/@lordned/unreal-engine-4-rendering-overview-part-1-c47f2da65346)
    
    7篇博文，[introduction&Setup](https://medium.com/@lordned/unreal-engine-4-rendering-overview-part-1-c47f2da65346), [Shaders and Vertex Factories](https://medium.com/@lordned/unreal-engine-4-rendering-part-2-shaders-and-vertex-data-80317e1ae5f3), [Drawing Policies and Drawing Policy Factories](https://medium.com/@lordned/unreal-engine-4-rendering-part-3-drawing-policies-89bb1a3c641b),[Shader Architecture](https://medium.com/@lordned/unreal-engine-4-rendering-part-4-the-deferred-shading-pipeline-389fc0175789), [Shader Iteration Tips](https://medium.com/@lordned/unreal-engine-4-rendering-part-5-shader-permutations-2b975e503dd4), [Tutorial on Adding a new Shading Model](https://medium.com/@lordned/ue4-rendering-part-6-adding-a-new-shading-model-e2972b40d72d), Modifying the Base Pass via Geometry shader 来介绍Unreal的Deferred Rendering Pipeline，以及如何添加新的自定义的Shadings Model。

9. [demystifying floating point precision](https://blog.demofox.org/2017/11/21/floating-point-precision/)
   
   浮点数值的精度以及遇到精度问题的解决方案。

10. [forward+ and cluster forward](https://docs.google.com/presentation/d/18yvym_tmSDnVC-mXRO9ykgP0RnBPoS5xgkzPt9EZNUk/edit#slide=id.p3)
   
   深入讲解了forward+和forward的区别和性能对比，以及cluster forward。

11. [Road to Anti-Aliasing in BRE: Aliasing and Anti-Aliasing](https://nbertoa.wordpress.com/2017/10/03/road-to-anti-aliasing-in-bre-aliasing-and-anti-aliasing/amp/)
     
     什么是锯齿？栅格化与锯齿？抗锯齿的技术：SMAA，MSAA，SSAA等等。

## 课程
1. [GAMES101: 现代计算机图形学入门](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html)
   
   > 本课程将全面而系统地介绍现代计算机图形学的四大组成部分：（1）光栅化成像，（2）几何表示，（3）光的传播理论，以及（4）动画与模拟。每个方面都会从基础原理出发讲解到实际应用，并介绍前沿的理论研究。通过本课程，你可以学习到计算机图形学背后的数学和物理知识，并锻炼实际的编程能力。

2. [GAMES201线上课程：高级物理引擎实战指南2020](https://zhuanlan.zhihu.com/p/144657172)
   
   > 本课程将会介绍基于物理的动画（Physically based animation）的基础和前沿知识，从拉格朗日、欧拉、混合欧拉-拉格朗日三大视角，介绍刚体、布料、烟雾、液体、弹塑性体（雪、泥沙、果冻、橡皮泥等）的模拟。通过本课程的学习，配合Taichi编程语言的使用，同学们可以独立从零开始编写最先进的高性能影视级物理求解器，并且利用自己的渲染器生成自己的特效动画。

## 资料

1. [AwesomeCppGameDev](https://github.com/Cmdu76/AwesomeCppGameDev)
    
    > Awesome list of C++ GameDev project