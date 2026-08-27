---
title: "PdfFileStamp.AddPageNumber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileStamp メソッド。ファイルにページ番号を追加します。ページ番号のテキストには # 記号を含めることができ、ページ番号に置き換えられます。ページ番号はページの下部に水平中央に配置されます。"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

ファイルにページ番号を追加します。ページ番号のテキストには # 記号を含めることができ、# はページ番号に置き換えられます。ページ番号はページの下部に水平中央に配置されます。

```csharp
public void AddPageNumber(string formatString)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formatString | String | ページ番号のテキスト |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

ページにページ番号を追加します。ページ番号には # 記号を含めることができ、# はページ番号に置き換えられます。ページ番号はページの下部に水平中央に配置されます。

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ページ番号の書式文字列は FormattedText として表されます。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### 関連項目

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

ドキュメントのページにページ番号を追加します。

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formatString | String | ページ番号の書式文字列。 |
| position | Int32 | ページ番号をページ上に配置する位置。0‑下部中央、1‑下部右、2‑上部右、3‑右側、4‑上部中央、5‑下部左、6‑左側、7‑上部左。次の定数を使用できます：PosBottomMiddle = 0、PosBottomRight = 1、PosUpperRight = 2、PosSidesRight = 3、PosUpperMiddle、PosBottomLeft = 5、PosSidesLeft、PosUpperLeft |
| leftMargin | Single | ページの左端の余白。 |
| rightMargin | Single | ページの右端の余白。 |
| topMargin | Single | ページの上端の余白。 |
| bottomMargin | Single | ページの下端の余白。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

ページ上の指定位置にページ番号を追加します。

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formatString | String | 書式文字列。書式文字列には # 記号を含めることができ、ページ番号に置き換えられます。 |
| x | Single | ページ番号の X 座標。 |
| y | Single | ページ番号の Y 座標。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

ドキュメントのページにページ番号を追加します。

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ページ番号の書式とテキストのプロパティを表す FormattedText オブジェクト。 |
| position | Int32 | ページ番号をページ上に配置する位置。0‑下部中央、1‑下部右、2‑上部右、3‑右側、4‑上部中央、5‑下部左、6‑左側、7‑上部左。次の定数を使用できます：PosBottomMiddle = 0、PosBottomRight = 1、PosUpperRight = 2、PosSidesRight = 3、PosUpperMiddle、PosBottomLeft = 5、PosSidesLeft、PosUpperLeft |
| leftMargin | Single | ページの左端の余白。 |
| rightMargin | Single | ページの右端の余白。 |
| topMargin | Single | ページの上端の余白。 |
| bottomMargin | Single | ページの下端の余白。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### 関連項目

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

ページ上の指定位置にページ番号を追加します。

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ページ番号の書式とテキストのプロパティを表すフォーマット済みテキスト。書式文字列には # 記号を含めることができ、ページ番号に置き換えられます。 |
| x | Single | ページ番号の X 座標。 |
| y | Single | ページ番号の Y 座標。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### 関連項目

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

ページにページ番号を追加します。

```csharp
public void AddPageNumber(string formatString, int position)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formatString | String | ページ番号の書式。このテキストには # が含まれ、ページ番号に置き換えられます。 |
| position | Int32 | ページ番号をページ上に配置する位置。0‑下部中央、1‑下部右、2‑上部右、3‑右側、4‑上部中央、5‑下部左、6‑左側、7‑上部左。次の定数を使用できます：PosBottomMiddle = 0、PosBottomRight = 1、PosUpperRight = 2、PosSidesRight = 3、PosUpperMiddle、PosBottomLeft = 5、PosSidesLeft、PosUpperLeft |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

ページにページ番号を追加します。

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ページ番号の書式とテキストプロパティを含む FormattedText オブジェクト。このテキストには # が含まれ、ページ番号に置き換えられます。 |
| position | Int32 | ページ番号をページ上に配置する位置。0‑下部中央、1‑下部右、2‑上部右、3‑右側、4‑上部中央、5‑下部左、6‑左側、7‑上部左。次の定数を使用できます：PosBottomMiddle = 0、PosBottomRight = 1、PosUpperRight = 2、PosSidesRight = 3、PosUpperMiddle、PosBottomLeft = 5、PosSidesLeft、PosUpperLeft |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### 関連項目

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


