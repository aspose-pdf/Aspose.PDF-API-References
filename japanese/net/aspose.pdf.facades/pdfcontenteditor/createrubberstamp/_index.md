---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。ラバースタンプ注釈を作成します。
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

ラバースタンプ注釈を作成します。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 注釈が作成される元のページの番号。 |
| annotRect | Rectangle | ページ上の注釈の位置を定義する注釈矩形。 |
| icon | String | 注釈を表示するために使用されるアイコン。デフォルト値: 'Draft'。 |
| annotContents | String | 注釈の内容。 |
| color | Color | 注釈の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 参照

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

ラバースタンプ注釈を作成します。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 注釈が作成される元のページの番号。 |
| annotRect | Rectangle | ページ上の注釈の位置を定義する注釈矩形。 |
| annotContents | String | 注釈の内容。 |
| color | Color | 注釈の色。 |
| appearanceFile | String | 外観ファイルのパス。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### 参照

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

ラバースタンプ注釈を作成します。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 注釈が作成される元のページの番号。 |
| annotRect | Rectangle | ページ上の注釈の位置を定義する注釈矩形。 |
| annotContents | String | 注釈の内容。 |
| color | Color | 注釈の色。 |
| appearanceStream | Stream | 外観ファイルのストリーム。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### 参照

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)