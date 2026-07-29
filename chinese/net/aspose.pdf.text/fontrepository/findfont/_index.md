---
title: "FontRepository.FindFont"
second_title: "Aspose.PDF for .NET API 参考"
description: "FontRepository 方法。搜索并返回指定字体名称的字体"
type: docs
weight: 40
url: /zh/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

搜索并返回具有指定字体名称的字体。

```csharp
public static Font FindFont(string fontName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 字体名称。 |

### 返回值

字体对象。

## 示例

示例演示如何查找字体并替换首页文本的字体。

```csharp
// 查找字体
Font font = FontRepository.FindFont("Arial");

// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次出现的文本的字体
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

搜索并返回具有指定字体名称的字体，忽略或遵守大小写敏感性。

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 字体名称。 |
| ignoreCase | Boolean | 大小写敏感性 |

### 返回值

字体对象。

## 示例

示例演示如何查找字体并替换首页文本的字体。

```csharp
// 查找字体
Font font = FontRepository.FindFont("Arial");

// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次出现的文本的字体
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

搜索并返回具有指定字体名称和字体样式的字体。

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFamilyName | String | 字体族名称。 |
| stl | FontStyles | 字体样式值。 |

### 返回值

对应搜索请求参数的字体对象。

## 示例

示例演示如何查找字体并替换首页文本的字体。

```csharp
// 查找字体
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现。
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首个文本出现的字体。
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

搜索并返回具有指定字体名称和字体样式的字体，忽略或遵守大小写敏感性。

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFamilyName | String | 字体族名称。 |
| stl | FontStyles | 字体样式值。 |
| ignoreCase | Boolean | 大小写敏感性 |

### 返回值

对应搜索请求参数的字体对象。

## 示例

示例演示如何查找字体并替换首页文本的字体。

```csharp
// 查找字体
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现。
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首个文本出现的字体。
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


