---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository 方法。使用指定的字体流打开字体
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

使用指定的字体流打开字体。

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontStream | Stream | 字体流。 |
| fontType | FontTypes | 字体类型值。 |

### 返回值

字体对象。

## 示例

该示例演示如何打开字体并替换第一页文本的字体。

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### 另请参阅

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

使用指定的字体文件路径打开字体。

```csharp
public static Font OpenFont(string fontFilePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFilePath | String | 字体文件路径。 |

### 返回值

字体对象。

## 示例

该示例演示如何打开字体并替换第一页文本的字体。

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

### 另请参阅

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

使用指定的字体文件路径和指标文件路径打开字体。

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFilePath | String | 字体文件路径。 |
| metricsFilePath | String | 字体指标文件路径。 |

### 返回值

字体对象。

## 示例

该示例演示如何打开 Type1 字体及其指标，并替换第一页文本的字体。

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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

### 另请参阅

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)