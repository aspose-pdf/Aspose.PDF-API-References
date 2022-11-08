---
title: ImageCompressionOptions
second_title: Aspose.PDF for Java API Reference
description: Class contains set  options for image compression.
type: docs
weight: 10
url: /java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ImageCompressionOptions
```

Class contains set options for image compression.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageCompressionOptions()](#ImageCompressionOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Gets or sets encoding used to store images. |
| [getImageQuality()](#getImageQuality--) | Specifies level of image compression when CompressIamges flag is used. |
| [getMaxResolution()](#getMaxResolution--) | Specifies maximum resolution of images. |
| [getResizeImages()](#getResizeImages--) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [getVersion()](#getVersion--) | Version of compression algorithm. |
| [hashCode()](#hashCode--) |  |
| [isCompressImages()](#isCompressImages--) | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [setEncoding(int value)](#setEncoding-int-) | Gets or sets encoding used to store images. |
| [setImageQuality(int value)](#setImageQuality-int-) | Specifies level of image compression when CompressIamges flag is used. |
| [setMaxResolution(int value)](#setMaxResolution-int-) | Specifies maximum resolution of images. |
| [setResizeImages(boolean value)](#setResizeImages-boolean-) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [setVersion(int value)](#setVersion-int-) | Version of compression algorithm. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageCompressionOptions() {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEncoding() {#getEncoding--}
```
public final int getEncoding()
```


Gets or sets encoding used to store images.

**Returns:**
int - ImageEncoding element
### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Specifies level of image compression when CompressIamges flag is used.

**Returns:**
int - int value
### getMaxResolution() {#getMaxResolution--}
```
public final int getMaxResolution()
```


Specifies maximum resolution of images. If image has higher resolition it will be scaled

**Returns:**
int - int value
### getResizeImages() {#getResizeImages--}
```
public final boolean getResizeImages()
```


If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.

**Returns:**
boolean - boolean value
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard".

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompressImages() {#isCompressImages--}
```
public final boolean isCompressImages()
```


If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setEncoding(int value) {#setEncoding-int-}
```
public final void setEncoding(int value)
```


Gets or sets encoding used to store images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ImageEncoding element |

### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Specifies level of image compression when CompressIamges flag is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setMaxResolution(int value) {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```


Specifies maximum resolution of images. If image has higher resolition it will be scaled

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setResizeImages(boolean value) {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```


If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

