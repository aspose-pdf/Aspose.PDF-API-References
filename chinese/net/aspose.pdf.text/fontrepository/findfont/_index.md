---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository 方法。搜索并返回指定字体名称的字体
type: docs
weight: 40
url: /zh/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

搜索并返回指定字体名称的字体。

```csharp
public static Font FindFont(string fontName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | 字符串 | 字体名称。 |

### 返回值

字体对象。

## 示例

该示例演示如何查找字体并替换第一页文本的字体。

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另见

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

搜索并返回指定字体名称的字体，忽略或尊重大小写敏感性。

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | 字符串 | 字体名称。 |
| ignoreCase | 布尔 | 大小写敏感性 |

### 返回值

字体对象。

## 示例

该示例演示如何查找字体并替换第一页文本的字体。

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另见

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

搜索并返回指定字体名称和字体样式的字体。

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFamilyName | 字符串 | 字体系列名称。 |
| stl | FontStyles | 字体样式值。 |

### 返回值

与搜索请求参数对应的字体对象。

## 示例

该示例演示如何查找字体并替换第一页文本的字体。

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另见

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

搜索并返回指定字体名称和字体样式的字体，忽略或尊重大小写敏感性。

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFamilyName | 字符串 | 字体系列名称。 |
| stl | FontStyles | 字体样式值。 |
| ignoreCase | 布尔 | 大小写敏感性 |

### 返回值

与搜索请求参数对应的字体对象。

## 示例

该示例演示如何查找字体并替换第一页文本的字体。

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另见

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)