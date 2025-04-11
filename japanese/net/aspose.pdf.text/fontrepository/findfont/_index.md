---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository メソッド。指定されたフォント名のフォントを検索して返します
type: docs
weight: 40
url: /ja/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

指定されたフォント名のフォントを検索して返します。

```csharp
public static Font FindFont(string fontName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | String | フォント名。 |

### 戻り値

フォントオブジェクト。

## 例

この例では、フォントを見つけて最初のページのテキストのフォントを置き換える方法を示します。

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

### 参照

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

指定されたフォント名のフォントを検索して返します。大文字と小文字の区別を無視するか尊重します。

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | String | フォント名。 |
| ignoreCase | Boolean | 大文字と小文字の区別 |

### 戻り値

フォントオブジェクト。

## 例

この例では、フォントを見つけて最初のページのテキストのフォントを置き換える方法を示します。

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

### 参照

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

指定されたフォント名とフォントスタイルのフォントを検索して返します。

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontFamilyName | String | フォントファミリ名。 |
| stl | FontStyles | フォントスタイル値。 |

### 戻り値

検索リクエストパラメータに対応するフォントオブジェクト。

## 例

この例では、フォントを見つけて最初のページのテキストのフォントを置き換える方法を示します。

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

### 参照

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

指定されたフォント名とフォントスタイルのフォントを検索して返します。大文字と小文字の区別を無視するか尊重します。

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontFamilyName | String | フォントファミリ名。 |
| stl | FontStyles | フォントスタイル値。 |
| ignoreCase | Boolean | 大文字と小文字の区別 |

### 戻り値

検索リクエストパラメータに対応するフォントオブジェクト。

## 例

この例では、フォントを見つけて最初のページのテキストのフォントを置き換える方法を示します。

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

### 参照

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)