---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建一个橡皮章注释
type: docs
weight: 260
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

创建一个橡皮章注释。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 创建注释的原始页面编号。 |
| annotRect | Rectangle | 定义注释在页面上位置的注释矩形。 |
| icon | String | 用于显示注释的图标。默认值：'Draft'。 |
| annotContents | String | 注释的内容。 |
| color | Color | 注释的颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

创建一个橡皮章注释。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 创建注释的原始页面编号。 |
| annotRect | Rectangle | 定义注释在页面上位置的注释矩形。 |
| annotContents | String | 注释的内容。 |
| color | Color | 注释的颜色。 |
| appearanceFile | String | 外观文件的路径。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

创建一个橡皮章注释。

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 创建注释的原始页面编号。 |
| annotRect | Rectangle | 定义注释在页面上位置的注释矩形。 |
| annotContents | String | 注释的内容。 |
| color | Color | 注释的颜色。 |
| appearanceStream | Stream | 外观文件的流。 |

## 示例

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

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)