---
title: PDF3DView
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类 PDF3DView。
type: docs
weight: 252
url: /zh/java/com.aspose.pdf/pdf3dview/
---
**遗产：**
java.lang.Object
```
public class PDF3DView
```

类 PDF3DView。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName)](#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.Matrix3D-double-java.lang.String-) | 初始化 PDF3DView 类的新实例。 |
| [PDF3DView(IDocument doc, PDF3DView view, String viewName)](#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.PDF3DView-java.lang.String-) | 初始化 PDF3DView 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackGroundColor()](#getBackGroundColor--) | 获取或设置视图背景的颜色。 |
| [getCameraOrbit()](#getCameraOrbit--) | 获取或设置相机视图轨道。 |
| [getCameraPosition()](#getCameraPosition--) | 获取或设置视图的相机位置。 |
| [getClass()](#getClass--) |  |
| [getCrossSectionsArray()](#getCrossSectionsArray--) | 获取视图的横截面数组。 |
| [getLightingScheme()](#getLightingScheme--) | 获取或设置视图的照明方案。 |
| [getRenderMode()](#getRenderMode--) | 获取或设置视图的渲染模式。 |
| [getViewName()](#getViewName--) | 获取或设置视图的名称。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackGroundColor(Color value)](#setBackGroundColor-com.aspose.pdf.Color-) | 获取或设置视图背景的颜色。 |
| [setCameraOrbit(double value)](#setCameraOrbit-double-) | 获取或设置相机视图轨道。 |
| [setCameraPosition(Matrix3D value)](#setCameraPosition-com.aspose.pdf.Matrix3D-) | 获取或设置视图的相机位置。 |
| [setLightingScheme(PDF3DLightingScheme value)](#setLightingScheme-com.aspose.pdf.PDF3DLightingScheme-) | 获取或设置视图的照明方案。 |
| [setRenderMode(PDF3DRenderMode value)](#setRenderMode-com.aspose.pdf.PDF3DRenderMode-) | 获取或设置视图的渲染模式。 |
| [setViewName(String value)](#setViewName-java.lang.String-) | 获取或设置视图的名称。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName) {#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.Matrix3D-double-java.lang.String-}
```
public PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName)
```


初始化 PDF3DView 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | 文档。 |
| cameraPosition | [Matrix3D](../../com.aspose.pdf/matrix3d) | 相机位置。 |
| cameraOrbit | double | 相机轨道。 |
| viewName | java.lang.String | 视图的名称。 |

### PDF3DView(IDocument doc, PDF3DView view, String viewName) {#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.PDF3DView-java.lang.String-}
```
public PDF3DView(IDocument doc, PDF3DView view, String viewName)
```


初始化 PDF3DView 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | 文档。 |
| view | [PDF3DView](../../com.aspose.pdf/pdf3dview) | 风景。 |
| viewName | java.lang.String | 视图的名称。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getBackGroundColor() {#getBackGroundColor--}
```
public Color getBackGroundColor()
```


获取或设置视图背景的颜色。

**退货：**
[Color](../../com.aspose.pdf/color) - 颜色值：视图背景的颜色。
### getCameraOrbit() {#getCameraOrbit--}
```
public double getCameraOrbit()
```


获取或设置相机视图轨道。

**退货：**
double - double 值：摄像机的视野轨道。
### getCameraPosition() {#getCameraPosition--}
```
public Matrix3D getCameraPosition()
```


获取或设置视图的相机位置。

**退货：**
[Matrix3D](../../com.aspose.pdf/matrix3d) - Matrix3D 对象：视图的相机位置。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCrossSectionsArray() {#getCrossSectionsArray--}
```
public PDF3DCrossSectionArray getCrossSectionsArray()
```


获取视图的横截面数组。

**退货：**
[PDF3DCrossSectionArray](../../com.aspose.pdf/pdf3dcrosssectionarray) - PDF3DCrossSectionArray 值：视图的横截面数组。
### getLightingScheme() {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```


获取或设置视图的照明方案。

**退货：**
[PDF3DLightingScheme](../../com.aspose.pdf/pdf3dlightingscheme) - PDF3DLightingScheme 对象：视图的光照方案。
### getRenderMode() {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```


获取或设置视图的渲染模式。

**退货：**
[PDF3DRenderMode](../../com.aspose.pdf/pdf3drendermode) - PDF3DRenderMode 值：视图的渲染模式。
### getViewName() {#getViewName--}
```
public String getViewName()
```


获取或设置视图的名称。

**退货：**
java.lang.String - 字符串对象 - 视图的名称。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackGroundColor(Color value) {#setBackGroundColor-com.aspose.pdf.Color-}
```
public void setBackGroundColor(Color value)
```


获取或设置视图背景的颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | ：视图背景的颜色。 |

### setCameraOrbit(double value) {#setCameraOrbit-double-}
```
public void setCameraOrbit(double value)
```


获取或设置相机视图轨道。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | ：相机的视野。 |

### setCameraPosition(Matrix3D value) {#setCameraPosition-com.aspose.pdf.Matrix3D-}
```
public void setCameraPosition(Matrix3D value)
```


获取或设置视图的相机位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix3D](../../com.aspose.pdf/matrix3d) | : Matrix3D - 视角的相机位置。 |

### setLightingScheme(PDF3DLightingScheme value) {#setLightingScheme-com.aspose.pdf.PDF3DLightingScheme-}
```
public void setLightingScheme(PDF3DLightingScheme value)
```


获取或设置视图的照明方案。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PDF3DLightingScheme](../../com.aspose.pdf/pdf3dlightingscheme) | PDF3DLightingScheme 对象：视图的光照方案。 |

### setRenderMode(PDF3DRenderMode value) {#setRenderMode-com.aspose.pdf.PDF3DRenderMode-}
```
public void setRenderMode(PDF3DRenderMode value)
```


获取或设置视图的渲染模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PDF3DRenderMode](../../com.aspose.pdf/pdf3drendermode) | : PDF3DRenderMode 对象，视图的渲染模式。 |

### setViewName(String value) {#setViewName-java.lang.String-}
```
public void setViewName(String value)
```


获取或设置视图的名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | ：视图的名称。 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
