---
title: "资源"
linktitle: "资源"
second_title: "Aspose.PDF for Java API 参考"
description: "表示页面资源的类。"
type: docs
weight: 4220
url: /zh/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

表示页面资源的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | 清除缓存数据，释放内存等。 |
| [getExtGStates](#getExtGStates--) | 获取资源中的所有 ExGStates。 |
| [getFonts](#getFonts--) | 获取 {@code Fonts} 资源集合 |
| [getFonts](#getFonts-boolean-) | 返回字体集合。如果资源不包含字体条目，则根据 CreateIfAbsent 标志创建。 |
| [getForms](#getForms--) | 获取 {@code Forms} 表单集合 |
| [getImages](#getImages--) | 获取 {@code Images} 图像集合 |
| [getResourceDictionary](#getResourceDictionary--) | 内部字段 |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | 获取资源 |
| [isCommonResource](#isCommonResource--) | 如果这些资源是公共的，即在多个页面之间共享（放置在页面字典中或作为对象引用放在每个页面中），则为 true。对公共资源的操作必须非常谨慎，例如在某一页面从公共资源中删除对象，若该对象被其他页面使用，可能导致其他页面出错。 |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | 仅供内部使用！ |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

清除缓存数据，释放内存等。

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

获取资源中的所有 ExGStates。

**Returns:**
返回包含 ExGStates 名称键的字典。

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

获取 {@code Fonts} 资源集合

**Returns:**
FontCollection 对象

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

返回字体集合。如果资源不包含字体条目，则根据 CreateIfAbsent 标志创建。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createIfAbsent |  | 如果此标志为 true，则在此条目缺失时将创建字体。 |

**Returns:**
字体集合。

### getForms {#getForms--}
```
public XFormCollection getForms()
```

获取 {@code Forms} 表单集合

**Returns:**
XFormCollection 对象

### getImages {#getImages--}
```
public XImageCollection getImages()
```

获取 {@code Images} 图像集合

**Returns:**
XImageCollection 对象

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

内部字段

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
获取资源

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

如果这些资源是公共的，即在多个页面之间共享（放置在页面字典中或作为对象引用放在每个页面中），则为 true。对公共资源的操作必须非常谨慎，例如在某一页面从公共资源中删除对象，若该对象被其他页面使用，可能导致其他页面出错。

**Returns:**
布尔值

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
仅供内部使用！
