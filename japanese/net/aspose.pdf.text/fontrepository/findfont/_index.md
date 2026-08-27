---
title: "FontRepository.FindFont"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FontRepository メソッド。指定されたフォント名のフォントを検索して返します"
type: docs
weight: 40
url: /ja/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

指定されたフォント名のフォントを検索して返します。

```csharp
public static Font FindFont(string fontName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | フォント名。 |

### 戻り値

フォント オブジェクト。

## 例

この例は、フォントを検索し、最初のページのテキストのフォントを置換する方法を示しています。

```csharp
// フォントを検索
Font font = FontRepository.FindFont("Arial");

// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントを変更
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

大文字小文字の区別を無視または考慮して、指定されたフォント名のフォントを検索して返します。

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | フォント名。 |
| ignoreCase | Boolean | 大文字小文字の区別 |

### 戻り値

フォント オブジェクト。

## 例

この例は、フォントを検索し、最初のページのテキストのフォントを置換する方法を示しています。

```csharp
// フォントを検索
Font font = FontRepository.FindFont("Arial");

// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントを変更
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fontFamilyName | String | フォント ファミリ名。 |
| stl | フォントスタイル | フォントスタイルの値。 |

### 戻り値

検索リクエストパラメータに対応するフォントオブジェクト。

## 例

この例は、フォントを検索し、最初のページのテキストのフォントを置換する方法を示しています。

```csharp
// フォントを検索
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキストの出現を見つけるために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現のフォントを変更します
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

大文字小文字の区別を無視または考慮して、指定されたフォント名とフォントスタイルのフォントを検索して返します。

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fontFamilyName | String | フォント ファミリ名。 |
| stl | フォントスタイル | フォントスタイルの値。 |
| ignoreCase | Boolean | 大文字小文字の区別 |

### 戻り値

検索リクエストパラメータに対応するフォントオブジェクト。

## 例

この例は、フォントを検索し、最初のページのテキストのフォントを置換する方法を示しています。

```csharp
// フォントを検索
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキストの出現を見つけるために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現のフォントを変更します
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


