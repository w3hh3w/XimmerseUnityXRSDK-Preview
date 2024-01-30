.. _2 设备及配件简介:

2.设备及配件简介
=================

此SDK目前主要支持RhinoX Pro及RhinoX2.0头显。

2.1 RhinoX Pro
------------------------

2.1.1 产品外观
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**头显设备及手柄控制器**

  .. image:: _static/proimage.png
    :height: 108px
    :width: 198px
    :align: Left
    :alt: RHinoX Pro头显
         
  .. image:: _static/proctrimage.png
    :height: 108px
    :width: 290px
    :align: Left
    :alt: RhinoX Pro控制器
    
|
|
|
|
|  
  
2.1.2 产品特性
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
RhinoX Pro相比上一代Rhino X主要有以下提升：

- **屏幕分辨率** 由原来的双眼2K提升到单眼2K
- 手柄升级到 **主动发光环形双手柄** ，性能实现质的飞跃
- 支持 **手势识别**
- 支持第一视角 **无线投屏**
- 同时支持 **有线串流** 以及无线串流
- 主控升级到 **XR2**，VIO定位性能提升明显

2.1.3 用户指南
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
RhinoX Pro设备详细使用说明及产品规格请查看 `RhinoX Pro使用说明书`_
  
.. _RhinoX Pro使用说明书: http://xms-developer.oss-cn-shenzhen.aliyuncs.com/release/unityxrsdk/RhinoX%20Pro_UserManual.pdf

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

.. 
  RhinoX2.0介绍
..

2.2 RhinoX 2.0
------------------------

2.2.1 产品图片
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**头显设备及手柄控制器**
  .. image:: _static/RhinoX2.0.png
    :height: 300px
    :width: 400px
    :align: Center
    :alt: Rhinox2.0头显

.. figure:: _static/proctrimage.png
    :height: 108px
    :width: 290px
    :align: Center
    :alt: Rhinox2.0控制器 
    
|    
2.2.2 产品特性
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
RhinoX 2.0 相较于RhinoX Pro主要有以下提升：

- 采用 **自由曲面棱镜** 光学方案，虚实对齐精度可达 **亚厘米级**
- 支持镜片 **电致变色** ，完美应对各种差异性环境
- 屏幕刷新率 **90HZ**
- 支持 **北斗和GPS双模定位**
- 配置 **TOF相机(深度相机)**
- 支持 **上视红外定位**，即可以识别头显上方的定位板



2.2.3 用户指南
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
RhinoX Pro设备详细使用说明及产品规格请查看 `RhinoX 2.0使用说明书`_

.. _RhinoX 2.0使用说明书: https://xms-developer.oss-cn-shenzhen.aliyuncs.com/release/unityxrsdk/RhinoX%202_UserManual.pdf

..
  配件说明
..

2.3 配件说明
------------

**Beacon定位板**

  .. image:: _static/Beacon定位板.png
    :height: 350px
    :width: 350px
    :align: left
    :alt: Beacon定位板

.. note::
  - 带有数字编号的纯黑色定位板有圆形及方形两种形状，功能一致。
  - 该定位板用于给头显定位使用，切勿使用彩色定位板进行定位。
    
**彩色定位板**

  .. image:: _static/彩色标定板.png
    :height: 250px
    :width: 250px
    :align: left
    :alt: 彩色定位板

.. note::
  - 彩色定位板通常用于支持 `ARKit (IOS)`_ 或者 `ARCore (Android)`_ 的移动端设备进行标定定位使用
  - 该标定板通常需要搭配Beacon定位板使用以对齐空间，使用方式为将Beacon定位板的数字编号对齐箭头方向即可使用。
.. _ARKit (IOS): https://developer.apple.com/cn/documentation/arkit/verifying_device_support_and_user_permission/
.. _ARCore (Android): https://developers.google.cn/ar/devices?hl=zh-cn





