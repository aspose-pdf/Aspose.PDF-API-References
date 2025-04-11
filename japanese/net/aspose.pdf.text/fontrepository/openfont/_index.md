---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository メソッド。指定されたフォントストリームでフォントを開きます
type: docs
weight: 60
url: /ja/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

指定されたフォントストリームでフォントを開きます。

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontStream | Stream | フォントストリーム。 |
| fontType | FontTypes | フォントタイプの値。 |

### 戻り値

フォントオブジェクト。

## 例

この例では、フォントを開き、最初のページのテキストのフォントを置き換える方法を示します。

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

### 参照

* クラス [Font](../../font/)
* 列挙 [FontTypes](../../fonttypes/)
* クラス [FontRepository](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

指定されたフォントファイルパスでフォントを開きます。

```csharp
public static Font OpenFont(string fontFilePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontFilePath | String | フォントファイルパス。 |

### 戻り値

フォントオブジェクト。

## 例

この例では、フォントを開き、最初のページのテキストのフォントを置き換える方法を示します。

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

### 参照

* クラス [Font](../../font/)
* クラス [FontRepository](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

指定されたフォントファイルパスとメトリクスファイルパスでフォントを開きます。

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontFilePath | String | フォントファイルパス。 |
| metricsFilePath | String | フォントメトリクスファイルパス。 |

### 戻り値

フォントオブジェクト。

## 例

この例では、メトリクスを持つ Type1 フォントを開き、最初のページのテキストのフォントを置き換える方法を示します。

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

### 参照

* クラス [Font](../../font/)
* クラス [FontRepository](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)