---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp メソッド。ドキュメントのページにフッターを追加します
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

ドキュメントのページにフッターを追加します。

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | フッターのテキストとテキストプロパティを含む FormattedText オブジェクト。 |
| bottomMargin | Single | ページの上部のマージン。 |

## 例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### 参照

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

ドキュメントのページにフッターを追加します。

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | フッターのテキストとテキストプロパティを含む FormattedText オブジェクト。 |
| bottomMargin | Single | ページの下部のマージン。 |
| leftMargin | Single | ページの左側のマージン。 |
| rightMargin | Single | ページの右側のマージン。 |

## 例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### 参照

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

画像をフッターとしてドキュメントのページに追加します。

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageFile | String | 画像ファイル名とパス。 |
| bottomMargin | Single | ページの下部のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### 参照

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

画像をページのフッターとして追加します。

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageFile | String | 画像ファイル名とパス。 |
| bottomMargin | Single | ページの下部のマージン。 |
| leftMargin | Single | ページの左側のマージン。 |
| rightMargin | Single | ページの右側のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### 参照

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

画像をページのフッターとして追加します。

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 画像データを含むストリーム。 |
| bottomMargin | Single | ページの下部のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### 参照

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

画像をページのフッターとして追加します。

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 画像データを含むストリーム。 |
| bottomMargin | Single | ページの下部のマージン。 |
| leftMargin | Single | ページの左側のマージン。 |
| rightMargin | Single | ページの右側のマージン。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### 参照

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)