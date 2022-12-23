---
title: PDF3DView
second_title: Aspose.PDF for Java API Reference
description: Class PDF3DView.
type: docs
weight: 253
url: /java/com.aspose.pdf/pdf3dview/
---
**Inheritance:**
java.lang.Object
```
public class PDF3DView
```

Class PDF3DView.
## Constructors

| Constructor | Description |
| --- | --- |
| [PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName)](#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.Matrix3D-double-java.lang.String-) | Initializes a new instance of the  PDF3DView  class. |
| [PDF3DView(IDocument doc, PDF3DView view, String viewName)](#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.PDF3DView-java.lang.String-) | Initializes a new instance of the  PDF3DView  class. |
## Methods

| Method | Description |
| --- | --- |
| [getLightingScheme()](#getLightingScheme--) | Gets or sets the lighting scheme of view. |
| [setLightingScheme(PDF3DLightingScheme value)](#setLightingScheme-com.aspose.pdf.PDF3DLightingScheme-) | Gets or sets the lighting scheme of view. |
| [getRenderMode()](#getRenderMode--) | Gets or sets the render mode of view. |
| [setRenderMode(PDF3DRenderMode value)](#setRenderMode-com.aspose.pdf.PDF3DRenderMode-) | Gets or sets the render mode of view. |
| [getCrossSectionsArray()](#getCrossSectionsArray--) | Gets the cross sections array of view. |
| [getViewName()](#getViewName--) | Gets or sets the name of the view. |
| [setViewName(String value)](#setViewName-java.lang.String-) | Gets or sets the name of the view. |
| [getCameraPosition()](#getCameraPosition--) | Gets or sets the camera position of view. |
| [setCameraPosition(Matrix3D value)](#setCameraPosition-com.aspose.pdf.Matrix3D-) | Gets or sets the camera position of view. |
| [getCameraOrbit()](#getCameraOrbit--) | Gets or sets the camera orbit of view. |
| [setCameraOrbit(double value)](#setCameraOrbit-double-) | Gets or sets the camera orbit of view. |
| [getBackGroundColor()](#getBackGroundColor--) | Gets or sets the color of the back ground of view. |
| [setBackGroundColor(Color value)](#setBackGroundColor-com.aspose.pdf.Color-) | Gets or sets the color of the back ground of view. |
### PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName) {#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.Matrix3D-double-java.lang.String-}
```
public PDF3DView(IDocument doc, Matrix3D cameraPosition, double cameraOrbit, String viewName)
```


Initializes a new instance of the  PDF3DView  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | The document. |
| cameraPosition | [Matrix3D](../../com.aspose.pdf/matrix3d) | The camera position. |
| cameraOrbit | double | The camera orbit. |
| viewName | java.lang.String | Name of the view. |

### PDF3DView(IDocument doc, PDF3DView view, String viewName) {#PDF3DView-com.aspose.pdf.IDocument-com.aspose.pdf.PDF3DView-java.lang.String-}
```
public PDF3DView(IDocument doc, PDF3DView view, String viewName)
```


Initializes a new instance of the  PDF3DView  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | The document. |
| view | [PDF3DView](../../com.aspose.pdf/pdf3dview) | The view. |
| viewName | java.lang.String | Name of the view. |

### getLightingScheme() {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```


Gets or sets the lighting scheme of view.

**Returns:**
[PDF3DLightingScheme](../../com.aspose.pdf/pdf3dlightingscheme) - PDF3DLightingScheme object: The lighting scheme of view.
### setLightingScheme(PDF3DLightingScheme value) {#setLightingScheme-com.aspose.pdf.PDF3DLightingScheme-}
```
public void setLightingScheme(PDF3DLightingScheme value)
```


Gets or sets the lighting scheme of view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PDF3DLightingScheme](../../com.aspose.pdf/pdf3dlightingscheme) | PDF3DLightingScheme object: The lighting scheme of view. |

### getRenderMode() {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```


Gets or sets the render mode of view.

**Returns:**
[PDF3DRenderMode](../../com.aspose.pdf/pdf3drendermode) - PDF3DRenderMode Value: The render mode of view.
### setRenderMode(PDF3DRenderMode value) {#setRenderMode-com.aspose.pdf.PDF3DRenderMode-}
```
public void setRenderMode(PDF3DRenderMode value)
```


Gets or sets the render mode of view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PDF3DRenderMode](../../com.aspose.pdf/pdf3drendermode) | : PDF3DRenderMode object, the render mode of view. |

### getCrossSectionsArray() {#getCrossSectionsArray--}
```
public PDF3DCrossSectionArray getCrossSectionsArray()
```


Gets the cross sections array of view.

**Returns:**
[PDF3DCrossSectionArray](../../com.aspose.pdf/pdf3dcrosssectionarray) - PDF3DCrossSectionArray Value: The cross sections array of view.
### getViewName() {#getViewName--}
```
public String getViewName()
```


Gets or sets the name of the view.

**Returns:**
java.lang.String - String object - the name of the view.
### setViewName(String value) {#setViewName-java.lang.String-}
```
public void setViewName(String value)
```


Gets or sets the name of the view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | : The name of the view. |

### getCameraPosition() {#getCameraPosition--}
```
public Matrix3D getCameraPosition()
```


Gets or sets the camera position of view.

**Returns:**
[Matrix3D](../../com.aspose.pdf/matrix3d) - Matrix3D object: The camera position of view.
### setCameraPosition(Matrix3D value) {#setCameraPosition-com.aspose.pdf.Matrix3D-}
```
public void setCameraPosition(Matrix3D value)
```


Gets or sets the camera position of view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix3D](../../com.aspose.pdf/matrix3d) | : Matrix3D - the camera position of view. |

### getCameraOrbit() {#getCameraOrbit--}
```
public double getCameraOrbit()
```


Gets or sets the camera orbit of view.

**Returns:**
double - double value: The camera orbit of view.
### setCameraOrbit(double value) {#setCameraOrbit-double-}
```
public void setCameraOrbit(double value)
```


Gets or sets the camera orbit of view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | : The camera orbit of view. |

### getBackGroundColor() {#getBackGroundColor--}
```
public Color getBackGroundColor()
```


Gets or sets the color of the back ground of view.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color Value: The color of the back ground of view.
### setBackGroundColor(Color value) {#setBackGroundColor-com.aspose.pdf.Color-}
```
public void setBackGroundColor(Color value)
```


Gets or sets the color of the back ground of view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | : The color of the back ground of view. |

