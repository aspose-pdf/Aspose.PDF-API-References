---
title: FontRepository
second_title: 用于 Java API 参考的 Aspose.PDF
description: 执行字体搜索。
type: docs
weight: 134
url: /zh/java/com.aspose.pdf/fontrepository/
---
**遗产：**
java.lang.Object
```
public final class FontRepository
```

执行字体搜索。搜索系统安装的字体和标准 Pdf 字体。还提供打开自定义字体的功能。

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  
  //查找字体
  Font font = FontRepository.findFont("Arial");
  
  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontRepository()](#FontRepository--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addLocalFontPath(String path)](#addLocalFontPath-java.lang.String-) | 再添加一条字体路径。 |
| [addSystemFont(Font font)](#addSystemFont-com.aspose.pdf.Font-) | 添加指定字体的系统字体。 |
| [clear()](#clear--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findFont(String fontName)](#findFont-java.lang.String-) | 搜索并返回具有指定字体名称的字体。 |
| [findFont(String fontName, boolean ignoreCase)](#findFont-java.lang.String-boolean-) | 搜索并返回具有指定字体名称的字体，忽略或区分大小写。 |
| [findFont(String fontFamilyName, int stl)](#findFont-java.lang.String-int-) | 搜索并返回具有指定字体名称和字体样式的字体。 |
| [findFont(String fontFamilyName, int stl, boolean ignoreCase)](#findFont-java.lang.String-int-boolean-) | 搜索并返回具有指定字体名称和字体样式的字体，忽略或区分大小写。 |
| [getClass()](#getClass--) |  |
| [getLocalFontPaths()](#getLocalFontPaths--) | 带有实际字体目录的列表副本。 |
| [getSources()](#getSources--) | 获取字体源集合。 |
| [getSubstitutions()](#getSubstitutions--) | 获取字体替换策略集合。 |
| [hashCode()](#hashCode--) |  |
| [isReplaceNotFoundFonts()](#isReplaceNotFoundFonts--) | 未找到的字体将替换为标准字体。 |
| [isThreadStaticConfigEnabled()](#isThreadStaticConfigEnabled--) | 返回字体源存储配置的状态。 |
| [loadFonts()](#loadFonts--) | 加载系统安装的字体和标准 Pdf 字体。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFont(InputStream fontStream, int fontType)](#openFont-java.io.InputStream-int-) | 使用指定的字体流打开字体。 |
| [openFont(String fontFilePath)](#openFont-java.lang.String-) | 打开具有指定字体文件路径的字体。 |
| [openFont(String fontFilePath, String metricsFilePath)](#openFont-java.lang.String-java.lang.String-) | 打开具有指定字体文件路径和规格文件路径的字体。 |
| [reloadFonts()](#reloadFonts--) | 重新加载属性 Sources (\#getSources.getSources) |
| [restoreLocalFontPath()](#restoreLocalFontPath--) | 默认恢复标准字体目录列表。 |
| [setLocalFontPaths(List<String> newFontPathsList)](#setLocalFontPaths-java.util.List-java.lang.String--) | 使用字体路径设置用户列表 |
| [setReplaceNotFoundFonts(boolean value)](#setReplaceNotFoundFonts-boolean-) | 如果需要用默认字体替换未找到的字体，请设置为 TRUE。 |
| [setThreadStaticConfigEnabled(boolean isTheadLocal)](#setThreadStaticConfigEnabled-boolean-) | 用于设置字体源存储配置的选项。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontRepository() {#FontRepository--}
```
public FontRepository()
```


### addLocalFontPath(String path) {#addLocalFontPath-java.lang.String-}
```
public static void addLocalFontPath(String path)
```


再添加一条字体路径。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 字符串值 |

### addSystemFont(Font font) {#addSystemFont-com.aspose.pdf.Font-}
```
public static void addSystemFont(Font font)
```


添加指定字体的系统字体。

--------------------

```
The example demonstrates how to add system font.

  InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf"))

  Font font = FontRepository.openFont(fontStream, FontTypes.TTF);

  FontRepository.addSystemFont(font);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) | 字体实例 |

### clear() {#clear--}
```
public static void clear()
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
### findFont(String fontName) {#findFont-java.lang.String-}
```
public static Font findFont(String fontName)
```


搜索并返回具有指定字体名称的字体。

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  //查找字体
  Font font = FontRepository.findFont("Arial");
  
  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体名称。 |

**退货：**
[Font](../../com.aspose.pdf/font) - 字体对象。
### findFont(String fontName, boolean ignoreCase) {#findFont-java.lang.String-boolean-}
```
public static Font findFont(String fontName, boolean ignoreCase)
```


搜索并返回具有指定字体名称的字体，忽略或区分大小写。

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  //查找字体
  Font font = FontRepository.findFont("Arial", FontStyles.Italic);
  
  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体名称。 |
| ignoreCase | boolean | 区分大小写 |

**退货：**
[Font](../../com.aspose.pdf/font) - 字体对象。
### findFont(String fontFamilyName, int stl) {#findFont-java.lang.String-int-}
```
public static Font findFont(String fontFamilyName, int stl)
```


搜索并返回具有指定字体名称和字体样式的字体。

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  //查找字体
  Font font = FontRepository.findFont("Arial", FontStyles.Italic);
  
  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontFamilyName | java.lang.String | 字体系列名称。 |
| stl | int | 字体样式值。 |

**退货：**
[Font](../../com.aspose.pdf/font) - 搜索请求参数对应的字体对象。
### findFont(String fontFamilyName, int stl, boolean ignoreCase) {#findFont-java.lang.String-int-boolean-}
```
public static Font findFont(String fontFamilyName, int stl, boolean ignoreCase)
```


搜索并返回具有指定字体名称和字体样式的字体，忽略或区分大小写。

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  //查找字体
  
  Font font = FontRepository.findFont("Arial", FontStyles.Italic, true);
  
  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontFamilyName | java.lang.String | 字体系列名称。 |
| stl | int | 字体样式值。 |
| ignoreCase | boolean | 区分大小写 |

**退货：**
[Font](../../com.aspose.pdf/font) - 搜索请求参数对应的字体对象。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getLocalFontPaths() {#getLocalFontPaths--}
```
public static List<String> getLocalFontPaths()
```


带有实际字体目录的列表副本。

**退货：**
java.util.List<java.lang.String> - 字符串列表
### getSources() {#getSources--}
```
public static FontSourceCollection getSources()
```


获取字体源集合。

**退货：**
[FontSourceCollection](../../com.aspose.pdf.text/fontsourcecollection) FontSourceCollection 对象
### getSubstitutions() {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```


获取字体替换策略集合。

**退货：**
[FontSubstitutionCollection](../../com.aspose.pdf.text/fontsubstitutioncollection) FontSubstitutionCollection 对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isReplaceNotFoundFonts() {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```


未找到的字体将替换为标准字体。

**退货：**
boolean - 布尔值
### isThreadStaticConfigEnabled() {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```


返回字体源存储配置的状态。
如果为真，则使用 ThreadStatic 并且每个线程都有自己的字体源。
如果为 false，则对所有线程使用全局静态配置。

--------------------

默认值为真。

**退货：**
boolean - 布尔值
### loadFonts() {#loadFonts--}
```
public static void loadFonts()
```


加载系统安装的字体和标准 Pdf 字体。此方法旨在加快字体加载过程。默认情况下，在首次请求任何字体时加载字体。使用此方法会在打开任何 Pdf 文档之前立即加载系统和标准 Pdf 字体。

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### openFont(InputStream fontStream, int fontType) {#openFont-java.io.InputStream-int-}
```
public static Font openFont(InputStream fontStream, int fontType)
```


使用指定的字体流打开字体。

--------------------

```
The example demonstrates how to open font and replace the font of text of first page.
  
  //打开字体
  InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf"))
  {
      Font font = FontRepository.openFont(fontStream, , FontTypes.TTF);
  
      //打开文档
      Document doc = new Document("D:\\Tests\\input.pdf");
      //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
      TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
      //接受第一页的吸收器
      doc.getPages().get_Item(1).accept(absorber);
  
      //更改第一个文本出现的字体
      absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
      //保存文件
      doc.save("D:\\Tests\\output.pdf"); 
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontStream | java.io.InputStream | 字体流。 |
| fontType | int | 字体类型值。 |

**退货：**
[Font](../../com.aspose.pdf/font) - 字体对象。
### openFont(String fontFilePath) {#openFont-java.lang.String-}
```
public static Font openFont(String fontFilePath)
```


打开具有指定字体文件路径的字体。

--------------------

```
The example demonstrates how to open font and replace the font of text of first page.
 
  //打开字体
  Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf");
  
  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontFilePath | java.lang.String | 字体文件路径。 |

**退货：**
[Font](../../com.aspose.pdf/font) - 字体对象。
### openFont(String fontFilePath, String metricsFilePath) {#openFont-java.lang.String-java.lang.String-}
```
public static Font openFont(String fontFilePath, String metricsFilePath)
```


打开具有指定字体文件路径和规格文件路径的字体。

--------------------

```
The example demonstrates how to open Type1 font with metrics and replace the font of text of first page.
  
  //打开字体
  Font font = FontRepository.openFont("courier.pfb", "courier.afm");
  
  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");
  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  //接受第一页的吸收器
  doc.getPages().get_Item(1).accept(absorber);
  
  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font);
  
  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontFilePath | java.lang.String | 字体文件路径。 |
| metricsFilePath | java.lang.String | 字体规格文件路径。 |

**退货：**
[Font](../../com.aspose.pdf/font) - 字体对象。
### reloadFonts() {#reloadFonts--}
```
public static void reloadFonts()
```


重新加载属性 Sources (\#getSources.getSources)

### restoreLocalFontPath() {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```


默认恢复标准字体目录列表。

### setLocalFontPaths(List<String> newFontPathsList) {#setLocalFontPaths-java.util.List-java.lang.String--}
```
public static void setLocalFontPaths(List<String> newFontPathsList)
```


使用字体路径设置用户列表

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newFontPathsList | java.util.List<java.lang.String> |  列表对象 |

### setReplaceNotFoundFonts(boolean value) {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```


如果需要用默认字体替换未找到的字体，请设置为 TRUE。默认值为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔值 | boolean |

### setThreadStaticConfigEnabled(boolean isTheadLocal) {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```


用于设置字体源存储配置的选项。
如果为真，则使用 ThreadStatic 并且每个线程都有自己的字体源。
如果为 false，则对所有线程使用全局静态配置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| isTheadLocal | boolean | 布尔值 |

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
