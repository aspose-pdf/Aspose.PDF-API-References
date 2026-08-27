---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 执行字体搜索。搜索系统已安装的字体和标准 Pdf 字体。还提供打开自定义字体的功能。 </p> <hr> <pre> 示例演示。"
type: docs
weight: 1690
url: /zh/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> 执行字体搜索。搜索系统已安装的字体和标准 Pdf 字体。还提供打开自定义字体的功能。 </p> <hr> <pre> 示例演示如何查找字体并替换第一页文本的字体。 // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | 为字体添加另一个路径。 |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> 添加具有指定字体的系统字体。 </p> <hr> <pre> 示例演示如何添加系统字体。 InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> 搜索并返回具有指定字体名称的字体。 </p> <hr> <pre> 示例演示如何查找字体并替换第一页文本的字体。 // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> 搜索并返回具有指定字体名称的字体，可选择是否区分大小写。 </p> <hr> <pre> 示例演示如何查找字体并替换第一页的字体。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> 搜索并返回具有指定字体名称和字体样式的字体。 </p> <hr> <pre> 示例演示如何查找字体并替换第一页的字体。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> 搜索并返回具有指定字体名称和字体样式的字体，可选择是否区分大小写。 </p> <hr> <pre> 示例演示如何查找字体并替换第一页的字体。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | 实际字体目录列表的副本。 |
| [getSources](#getSources--) | 获取字体来源集合。 |
| [getSubstitutions](#getSubstitutions--) | 获取字体替代策略集合。 |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | 未找到的字体将被标准字体替代。 |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> 返回 Font Sources 存储配置的状态。 <br> 如果为 true，使用 ThreadStatic，每个线程拥有自己的 Font Sources。 <br> 如果为 false，使用全局静态配置，所有线程共享。 </p> <hr> 默认值为 True。 |
| [loadFonts](#loadFonts--) | 加载系统已安装的字体和标准 PDF 字体。此方法旨在加快字体加载过程。默认情况下，字体在首次请求任意字体时才加载。使用此方法可在打开任何 PDF 文档之前立即加载系统和标准 PDF 字体。 |
| [openFont](#openFont-java.io.InputStream-int-) | <p> 使用指定的字体流打开字体。 </p> <hr> <pre> 示例演示了如何打开字体并替换首页文本的字体。 // Open font InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> 使用指定的字体文件路径打开字体。 </p> <hr> <pre> 示例演示了如何打开字体并替换首页文本的字体。 // Open font Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> 使用指定的字体文件路径和度量文件路径打开字体。 </p> <hr> <pre> 示例演示了如何使用度量文件打开 Type1 字体并替换首页文本的字体。 // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | 重新加载属性 {@code Sources}（{@link #getSources}）指定的所有字体 |
| [restoreLocalFontPath](#restoreLocalFontPath--) | 默认情况下恢复标准字体目录列表。 |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | 设置包含字体路径的用户列表 |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | 如果需要用默认字体替换未找到的字体，请设置为 TRUE。默认值为 false。 |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | 用于设置 Font Sources 存储配置的选项。若为 true，使用 ThreadStatic，每个线程拥有自己的 Font Sources。若为 false，使用全局静态配置，所有线程共享。 |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
为字体添加另一个路径。

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> 使用指定的字体添加系统字体。 </p> <hr> <pre> 示例演示了如何添加系统字体。 InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> 搜索并返回指定字体名称的字体。 </p> <hr> <pre> 示例演示了如何查找字体并替换首页文本的字体。 // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> 搜索并返回指定字体名称的字体，可选择是否区分大小写。 </p> <hr> <pre> 示例演示了如何查找字体并替换首页文本的字体。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> 搜索并返回指定字体名称和字体样式的字体。 </p> <hr> <pre> 示例演示了如何查找字体并替换首页文本的字体。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> 搜索并返回具有指定字体名称和字体样式的字体，可选择是否区分大小写。 </p> <hr> <pre> 示例演示如何查找字体并替换第一页文本的字体。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

实际字体目录列表的副本。

**Returns:**
字符串列表

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

获取字体来源集合。

**Returns:**
FontSourceCollection 对象

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

获取字体替代策略集合。

**Returns:**
FontSubstitutionCollection 对象

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

未找到的字体将被标准字体替代。

**Returns:**
布尔值

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> 返回 Font Sources 存储配置的状态。 <br> 如果为 true，使用 ThreadStatic，每个线程拥有自己的 Font Sources。 <br> 如果为 false，使用全局静态配置，所有线程共享。 </p> <hr> 默认值为 True。

**Returns:**
布尔值

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

加载系统已安装的字体和标准 PDF 字体。此方法旨在加快字体加载过程。默认情况下，字体在首次请求任意字体时才加载。使用此方法可在打开任何 PDF 文档之前立即加载系统和标准 PDF 字体。

### openFont {#openFont-java.io.InputStream-int-}
<p> 使用指定的字体流打开字体。 </p> <hr> <pre> 示例演示如何打开字体并替换第一页文本的字体。 // Open font InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> 使用指定的字体文件路径打开字体。 </p> <hr> <pre> 示例演示如何打开字体并替换第一页文本的字体。 // Open font Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> 使用指定的字体文件路径和度量文件路径打开字体。 </p> <hr> <pre> 示例演示如何打开带度量的 Type1 字体并替换第一页文本的字体。 // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

重新加载属性 {@code Sources}（{@link #getSources}）指定的所有字体

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

默认情况下恢复标准字体目录列表。

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
设置包含字体路径的用户列表

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

如果需要用默认字体替换未找到的字体，请设置为 TRUE。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔型 |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

用于设置 Font Sources 存储配置的选项。若为 true，使用 ThreadStatic，每个线程拥有自己的 Font Sources。若为 false，使用全局静态配置，所有线程共享。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isTheadLocal |  | 布尔值 |
