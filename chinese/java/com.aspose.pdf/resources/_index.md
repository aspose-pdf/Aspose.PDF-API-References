---
title: Resources
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示页面资源的类。
type: docs
weight: 310
url: /zh/java/com.aspose.pdf/resources/
---
**遗产：**
java.lang.Object
```
public final class Resources
```

表示页面资源的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [clearImagesCache()](#clearImagesCache--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFonts()](#getFonts--) | 获取字体资源集合 |
| [getFonts(boolean createIfAbsent)](#getFonts-boolean-) | 返回字体集合。 |
| [getForms()](#getForms--) | 获取 Forms 表单集合 |
| [getImages()](#getImages--) | 获取Images图像集合 |
| [getResourcesFor(Form form)](#getResourcesFor-com.aspose.pdf.Form-) | 获取资源 |
| [hashCode()](#hashCode--) |  |
| [isCommonResource()](#isCommonResource--) | 如果此资源是公共的，即为多个页面共享（放置在页面字典中或作为对象引用在每个页面中），则为真 必须非常小心地执行对公共资源的操作，例如，从一个页面中的公共资源中删除对象可能会导致其他页面出现错误如果删除的对象用于其他页面。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setResourceDictionary(IResourceDictionary resourceDictionary)](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | 仅供内部使用！ |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearImagesCache() {#clearImagesCache--}
```
public final void clearImagesCache()
```




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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


获取字体资源集合

**退货：**
[FontCollection](../../com.aspose.pdf/fontcollection) - 字体集合对象
### getFonts(boolean createIfAbsent) {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```


返回字体集合。如果资源不包含字体条目，它将根据 CreateIfAbsent 标志创建。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createIfAbsent | boolean | 如果此标志为真，则在缺少此条目时将创建字体。 |

**退货：**
[FontCollection](../../com.aspose.pdf/fontcollection) - 字体集合。
### getForms() {#getForms--}
```
public XFormCollection getForms()
```


获取 Forms 表单集合

**退货：**
[XFormCollection](../../com.aspose.pdf/xformcollection) - XFormCollection 对象
### getImages() {#getImages--}
```
public XImageCollection getImages()
```


获取Images图像集合

**退货：**
[XImageCollection](../../com.aspose.pdf/ximagecollection) XImageCollection 对象
### getResourcesFor(Form form) {#getResourcesFor-com.aspose.pdf.Form-}
```
public static Resources getResourcesFor(Form form)
```


获取资源

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| form | [Form](../../com.aspose.pdf/form) | 表单对象 |

**退货：**
[Resources](../../com.aspose.pdf/resources) 资源对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isCommonResource() {#isCommonResource--}
```
public boolean isCommonResource()
```


如果此资源是公共的，即为多个页面共享（放置在页面字典中或作为对象引用在每个页面中），则为真 必须非常小心地执行对公共资源的操作，例如，从一个页面中的公共资源中删除对象可能会导致其他页面出现错误如果删除的对象用于其他页面。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setResourceDictionary(IResourceDictionary resourceDictionary) {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
```
public void setResourceDictionary(IResourceDictionary resourceDictionary)
```


仅供内部使用！

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resourceDictionary | [IResourceDictionary](../../com.aspose.pdf.engine.commondata.pagecontent/iresourcedictionary) | 内部实例 |

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
