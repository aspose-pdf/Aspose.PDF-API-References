---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp メソッド。ファイルにページ番号を追加します。ページ番号のテキストには # 記号が含まれる場合があり、これはページの番号に置き換えられます。ページ番号はページの下部に水平に中央揃えで配置されます。
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

ファイルにページ番号を追加します。ページ番号のテキストには # 記号が含まれる場合があり、これはページの番号に置き換えられます。ページ番号はページの下部に水平に中央揃えで配置されます。

```csharp
public void AddPageNumber(string formatString)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formatString | String | ページ番号のテキスト |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### 参照

* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

ページにページ番号を追加します。ページ番号には # 記号が含まれる場合があり、これはページ番号に置き換えられます。ページ番号はページの下部に水平に中央揃えで配置されます。

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText として表されるページ番号のフォーマット文字列。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### 参照

* クラス [FormattedText](../../formattedtext/)
* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

ドキュメントのページにページ番号を追加します。

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formatString | String | ページ番号のフォーマット文字列。 |
| position | Int32 | ページ番号がページに配置される位置。0-下中央、1-下右、2-上右、3-右側、4-上中央、5-下左、6-左側、7-上左。次の定数を使用できます: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | ページの左端のマージン。 |
| rightMargin | Single | ページの右端のマージン。 |
| topMargin | Single | ページの上端のマージン。 |
| bottomMargin | Single | ページの下端のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 参照

* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

指定された位置にページ番号を追加します。

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formatString | String | フォーマット文字列。フォーマット文字列にはページ番号に置き換えられる # 記号が含まれる場合があります。 |
| x | Single | ページ番号の X 座標。 |
| y | Single | ページ番号の Y 座標。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 参照

* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

ドキュメントのページにページ番号を追加します。

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ページ番号のフォーマットとテキストのプロパティを表す FormattedText オブジェクト。 |
| position | Int32 | ページ番号がページに配置される位置。0-下中央、1-下右、2-上右、3-右側、4-上中央、5-下左、6-左側、7-上左。次の定数を使用できます: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | ページの左端のマージン。 |
| rightMargin | Single | ページの右端のマージン。 |
| topMargin | Single | ページの上端のマージン。 |
| bottomMargin | Single | ページの下端のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 参照

* クラス [FormattedText](../../formattedtext/)
* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

指定された位置にページ番号を追加します。

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ページ番号のフォーマットとテキストのプロパティを表すフォーマットされたテキスト。フォーマット文字列にはページ番号に置き換えられる # 記号が含まれる場合があります。 |
| x | Single | ページ番号の X 座標。 |
| y | Single | ページ番号の Y 座標。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 参照

* クラス [FormattedText](../../formattedtext/)
* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

ページにページ番号を追加します。

```csharp
public void AddPageNumber(string formatString, int position)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formatString | String | ページ番号のフォーマット。このテキストにはページ番号に置き換えられる # が含まれる場合があります。 |
| position | Int32 | ページ番号がページに配置される位置。0-下中央、1-下右、2-上右、3-右側、4-上中央、5-下左、6-左側、7-上左。次の定数を使用できます: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 参照

* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

ページにページ番号を追加します。

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ページ番号のフォーマットとテキストのプロパティを含む FormattedText オブジェクト。このテキストにはページ番号に置き換えられる # が含まれる場合があります。 |
| position | Int32 | ページ番号がページに配置される位置。0-下中央、1-下右、2-上右、3-右側、4-上中央、5-下左、6-左側、7-上左。次の定数を使用できます: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 参照

* クラス [FormattedText](../../formattedtext/)
* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)