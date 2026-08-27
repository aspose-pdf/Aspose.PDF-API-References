---
title: "PdfFileStamp.AddFooter"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileStamp メソッド。ドキュメントのページにフッターを追加します"
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

ドキュメントのページにフッターを追加します。

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText オブジェクト。フッターのテキストとテキストプロパティを含みます。 |
| bottomMargin | Single | ページ上部の余白。 |

## 例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText オブジェクト。フッターのテキストとテキストプロパティを含みます。 |
| bottomMargin | Single | ページ下部の余白。 |
| leftMargin | Single | ページ左側の余白。 |
| rightMargin | Single | ページ右側の余白。 |

## 例

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### 関連項目

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

ドキュメントのページにフッターとして画像を追加します。

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageFile | String | 画像ファイル名とパス。 |
| bottomMargin | Single | ページ下部の余白。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

ページのフッターとして画像を追加します。

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageFile | String | 画像ファイル名とパス。 |
| bottomMargin | Single | ページ下部の余白。 |
| leftMargin | Single | ページ左側の余白。 |
| rightMargin | Single | ページ右側の余白。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

ページのフッターとして画像を追加します。

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageStream | Stream | ストリームには画像データが含まれています。 |
| bottomMargin | Single | ページ下部の余白。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

ページのフッターとして画像を追加します。

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageStream | Stream | ストリームには画像データが含まれています。 |
| bottomMargin | Single | ページ下部の余白。 |
| leftMargin | Single | ページ左側の余白。 |
| rightMargin | Single | ページ右側の余白。 |

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


