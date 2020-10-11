# 周报 第15期

## blog

* [per object clipping planes shader in unity3d](http://www.toxicfork.com/194/per-object-clipping-planes-shader-in-unity3d-5)
    自定义裁剪平面，即当渲染物体与裁剪平面相交，可以隐藏相交的部分。作者通过扩展Unity自带的standard着色器和点到平面的距离的几何原理，在片段着色器中clip掉相交的片段。

* [Screen Space Planar Reflections in Ghost Recon Wildlands](http://remi-genin.fr/blog/screen-space-plane-indexed-reflection-in-ghost-recon-wildlands/)
     SSR技术常用于表现反射现象，如水面反射。SSPR是SSR的一种变体，更好性能和更好的画面表现。其基本原理是：projection和resolve。投射过程引入了一个新概念**Projection Hash Buffer**，用来存储平面反射适口屏幕空间的片段对应的主适口的屏幕空间位置。resolve就是根据Projection Hash Buffer的主适口的屏幕空间位置获取主适口画面的片段，生成反射纹理。该方法有两个主要缺陷：闪烁和缝隙。文章也给出了具体的解决方案以及如何支持多个水面反射。

* [Unity URP 移动平台的屏幕空间平面反射(SSPR)趟坑记](https://zhuanlan.zhihu.com/p/150890059)
     如题。如何在Unity中实现SSPR效果。

* [Unreal Art Optimization](https://unrealartoptimization.github.io/book/)
     UE4 艺术优化的在线书籍。（作者一直在陆续更新中）