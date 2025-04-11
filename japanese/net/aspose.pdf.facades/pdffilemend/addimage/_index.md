---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: PdfFileMend メソッド。指定された座標でPDFドキュメントの指定されたページに画像を追加します
type: docs
weight: 50
url: /ja/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

指定された座標でPDFドキュメントの指定されたページに画像を追加します。

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 入力画像ストリーム。 |
| pageNum | Int32 | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像の矩形の左下のx。 |
| lowerLeftY | Single | 画像の矩形の左下のy。 |
| upperRightX | Single | 画像の矩形の右上のx。 |
| upperRightY | Single | 画像の矩形の右上のy。 |

### 戻り値

成功した場合はTrue、そうでない場合はFalse。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### 関連項目

* クラス [PdfFileMend](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

指定された座標でPDFドキュメントの指定されたページに画像を追加します。

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 入力画像ストリーム。 |
| pageNum | Int32 | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像の矩形の左下のx。 |
| lowerLeftY | Single | 画像の矩形の左下のy。 |
| upperRightX | Single | 画像の矩形の右上のx。 |
| upperRightY | Single | 画像の矩形の右上のy。 |
| compositingParameters | CompositingParameters | 画像のグラフィックス合成パラメータ。 |

### 戻り値

成功した場合はTrue、そうでない場合はFalse。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### 関連項目

* クラス [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* クラス [PdfFileMend](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

指定された座標でPDFドキュメントの指定されたページに画像を追加します。

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 入力画像ストリーム。 |
| pageNums | Int32[] | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像の矩形の左下のx。 |
| lowerLeftY | Single | 画像の矩形の左下のy。 |
| upperRightX | Single | 画像の矩形の右上のx。 |
| upperRightY | Single | 画像の矩形の右上のy。 |

### 戻り値

成功した場合はTrue、そうでない場合はFalse。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### 関連項目

* クラス [PdfFileMend](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

指定された座標でPDFドキュメントの指定されたページに画像を追加します。

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 入力画像ストリーム。 |
| pageNums | Int32[] | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像の矩形の左下のx。 |
| lowerLeftY | Single | 画像の矩形の左下のy。 |
| upperRightX | Single | 画像の矩形の右上のx。 |
| upperRightY | Single | 画像の矩形の右上のy。 |
| compositingParameters | CompositingParameters | 画像のグラフィックス合成パラメータ。 |

### 戻り値

成功した場合はTrue、そうでない場合はFalse。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### 関連項目

* クラス [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* クラス [PdfFileMend](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

指定された座標でPDFドキュメントの指定されたページに画像を追加します。

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageName | String | 入力画像ファイルのパス。 |
| pageNum | Int32 | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像の矩形の左下のx。 |
| lowerLeftY | Single | 画像の矩形の左下のy。 |
| upperRightX | Single | 画像の矩形の右上のx。 |
| upperRightY | Single | 画像の矩形の右上のy。 |

### 戻り値

成功した場合はTrue、そうでない場合はFalse。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 関連項目

* クラス [PdfFileMend](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

指定された座標でPDFドキュメントの指定されたページに画像を追加します。

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageName | String | 入力画像ファイルのパス。 |
| pageNum | Int32 | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像の矩形の左下のx。 |
| lowerLeftY | Single | 画像の矩形の左下のy。 |
| upperRightX | Single | 画像の矩形の右上のx。 |
| upperRightY | Single | 画像の矩形の右上のy。 |
| compositingParameters | CompositingParameters | 画像のグラフィックス合成パラメータ。 |

### 戻り値

成功した場合はTrue、そうでない場合はFalse。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 関連項目

* クラス [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* クラス [PdfFileMend](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

指定された座標でPDFドキュメントの指定されたページに画像を追加します。

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageName | String | 入力画像ファイルのパス。 |
| pageNums | Int32[] | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像の矩形の左下のx。 |
| lowerLeftY | Single | 画像の矩形の左下のy。 |
| upperRightX | Single | 画像の矩形の右上のx。 |
| upperRightY | Single | 画像の矩形の右上のy。 |

### 戻り値

成功した場合はTrue、そうでない場合はFalse。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 関連項目

* クラス [PdfFileMend](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

指定された座標でPDFドキュメントの指定されたページに画像を追加します。

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageName | String | 入力画像ファイルのパス。 |
| pageNums | Int32[] | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像の矩形の左下のx。 |
| lowerLeftY | Single | 画像の矩形の左下のy。 |
| upperRightX | Single | 画像の矩形の右上のx。 |
| upperRightY | Single | 画像の矩形の右上のy。 |
| compositingParameters | CompositingParameters | 画像のグラフィックス合成パラメータ。 |

### 戻り値

成功した場合はTrue、そうでない場合はFalse。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 関連項目

* クラス [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* クラス [PdfFileMend](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)