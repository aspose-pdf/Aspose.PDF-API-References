---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp メソッド。ページにヘッダーを追加します。
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

ページにヘッダーを追加します。

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ヘッダー用のテキストとテキストのプロパティ。 |
| topMargin | Single | ページの上部のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### 参照

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

ファイルのページにヘッダーを追加します。

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | ページテキストとそのプロパティを含むフォーマットされたテキストオブジェクト。 |
| topMargin | Single | ページの上部のマージン。 |
| leftMargin | Single | ページの左側のマージン。 |
| rightMargin | Single | ページの右側のマージン。 |

## 例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### 参照

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

ファイルのページに画像をヘッダーとして追加します。

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageFile | String | 画像ファイルへのパス。 |
| topMargin | Single | ページの上部のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### 参照

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

ページに画像をヘッダーとして追加します。

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageFile | String | 画像ファイルへのパス。 |
| topMargin | Single | ページの上部のマージン。 |
| leftMargin | Single | ページの左側のマージン。 |
| rightMargin | Single | ページの右側のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### 参照

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

ページに画像をヘッダーとして追加します。

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 画像のストリーム。 |
| topMargin | Single | ページの上部のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### 参照

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

ページの上部に画像を追加します。

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 画像データを含むストリーム。 |
| topMargin | Single | ページの上部のマージン。 |
| leftMargin | Single | ページの左側のマージン。 |
| rightMargin | Single | ページの右側のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### 参照

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)