---
title: "PdfFileMend.AddImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileMend メソッド。指定された座標で PDF ドキュメントの指定ページに画像を追加します。"
type: docs
weight: 50
url: /ja/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

指定された座標で PDF Document の指定 Page に画像を追加します。

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageStream | Stream | 入力画像ストリーム。 |
| pageNum | Int32 | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像矩形の左下 X。 |
| lowerLeftY | Single | 画像矩形の左下 Y。 |
| upperRightX | Single | 画像矩形の右上 X。 |
| upperRightY | Single | 画像矩形の右上 Y。 |

### 戻り値

成功した場合は True、そうでない場合は false。

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

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

指定された座標で PDF Document の指定 Page に画像を追加します。

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageStream | Stream | 入力画像ストリーム。 |
| pageNum | Int32 | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像矩形の左下 X。 |
| lowerLeftY | Single | 画像矩形の左下 Y。 |
| upperRightX | Single | 画像矩形の右上 X。 |
| upperRightY | Single | 画像矩形の右上 Y。 |
| compositingParameters | CompositingParameters | 画像のグラフィック合成パラメータ。 |

### 戻り値

成功した場合は True、そうでない場合は false。

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

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

指定された座標で PDF Document の指定 Page に画像を追加します。

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageStream | Stream | 入力画像ストリーム。 |
| pageNums | Int32[] | 画像を受け取るページの数。 |
| lowerLeftX | Single | 画像矩形の左下 X。 |
| lowerLeftY | Single | 画像矩形の左下 Y。 |
| upperRightX | Single | 画像矩形の右上 X。 |
| upperRightY | Single | 画像矩形の右上 Y。 |

### 戻り値

成功した場合は True、そうでない場合は false。

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

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

指定された座標で PDF Document の指定 Page に画像を追加します。

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageStream | Stream | 入力画像ストリーム。 |
| pageNums | Int32[] | 画像を受け取るページの数。 |
| lowerLeftX | Single | 画像矩形の左下 X。 |
| lowerLeftY | Single | 画像矩形の左下 Y。 |
| upperRightX | Single | 画像矩形の右上 X。 |
| upperRightY | Single | 画像矩形の右上 Y。 |
| compositingParameters | CompositingParameters | 画像のグラフィック合成パラメータ。 |

### 戻り値

成功した場合は True、そうでない場合は false。

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

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

指定された座標で PDF Document の指定 Page に画像を追加します。

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageName | String | 入力画像ファイルのパス。 |
| pageNum | Int32 | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像矩形の左下 X。 |
| lowerLeftY | Single | 画像矩形の左下 Y。 |
| upperRightX | Single | 画像矩形の右上 X。 |
| upperRightY | Single | 画像矩形の右上 Y。 |

### 戻り値

成功した場合は True、そうでない場合は false。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 関連項目

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

指定された座標で PDF Document の指定 Page に画像を追加します。

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageName | String | 入力画像ファイルのパス。 |
| pageNum | Int32 | 画像を受け取るページの番号。 |
| lowerLeftX | Single | 画像矩形の左下 X。 |
| lowerLeftY | Single | 画像矩形の左下 Y。 |
| upperRightX | Single | 画像矩形の右上 X。 |
| upperRightY | Single | 画像矩形の右上 Y。 |
| compositingParameters | CompositingParameters | 画像のグラフィック合成パラメータ。 |

### 戻り値

成功した場合は True、そうでない場合は false。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 関連項目

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

指定された座標で PDF Document の指定 Page に画像を追加します。

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageName | String | 入力画像ファイルのパス。 |
| pageNums | Int32[] | 画像を受け取るページの数。 |
| lowerLeftX | Single | 画像矩形の左下 X。 |
| lowerLeftY | Single | 画像矩形の左下 Y。 |
| upperRightX | Single | 画像矩形の右上 X。 |
| upperRightY | Single | 画像矩形の右上 Y。 |

### 戻り値

成功した場合は True、そうでない場合は false。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### 関連項目

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

指定された座標で PDF Document の指定 Page に画像を追加します。

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageName | String | 入力画像ファイルのパス。 |
| pageNums | Int32[] | 画像を受け取るページの数。 |
| lowerLeftX | Single | 画像矩形の左下 X。 |
| lowerLeftY | Single | 画像矩形の左下 Y。 |
| upperRightX | Single | 画像矩形の右上 X。 |
| upperRightY | Single | 画像矩形の右上 Y。 |
| compositingParameters | CompositingParameters | 画像のグラフィック合成パラメータ。 |

### 戻り値

成功した場合は True、そうでない場合は false。

## 例

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### 関連項目

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


