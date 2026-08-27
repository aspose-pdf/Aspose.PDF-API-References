---
title: "PdfContentEditor.CreateRubberStamp"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。ゴムスタンプ アノテーションを作成します"
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

ゴムスタンプ注釈を作成します。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |
| annotRect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| icon | String | アノテーションの表示に使用されるアイコンです。デフォルト値: 'Draft'。 |
| annotContents | String | アノテーションの内容です。 |
| color | Color | アノテーションの色です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

ゴムスタンプ注釈を作成します。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |
| annotRect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| annotContents | String | アノテーションの内容です。 |
| color | Color | 注釈の色です。 |
| appearanceFile | String | 外観ファイルのパスです。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

ゴムスタンプ注釈を作成します。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |
| annotRect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| annotContents | String | アノテーションの内容です。 |
| color | Color | 注釈の色です。 |
| appearanceStream | Stream | 外観ファイルのストリームです。 |

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

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


