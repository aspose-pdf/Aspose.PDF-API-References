---
title: "PdfContentEditor.CreateFileAttachment"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建文件附件注释。"
type: docs
weight: 150
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

创建文件附件注释。

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| 内容 | String | 注释的内容。 |
| filePath | String | 将附加文件的路径。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| 名称 | String | 将在显示注释时使用图标的名称。该值可以是："Graph"、"PushPin"、"Paperclip"、"Tag"。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

创建文件附件注释。

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| 内容 | String | 注释的内容。 |
| filePath | String | 将附加文件的路径。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| 名称 | String | 将在显示注释时使用图标的名称。该值可以是："Graph"、"PushPin"、"Paperclip"、"Tag"。 |
| 不透明度 | Double | 图标的不透明度范围为 0 到 1：0 - 完全透明，1 - 完全不透明。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

创建文件附件注释。

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| 内容 | String | 注释的内容。 |
| attachmentStream | Stream | 附件文件流。 |
| attachmentName | String | 附件名称。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| 名称 | String | 将在显示注释时使用图标的名称。该值可以是："Graph"、"PushPin"、"Paperclip"、"Tag"。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

创建文件附件注释。

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| 内容 | String | 注释的内容。 |
| attachmentStream | Stream | 附件文件流。 |
| attachmentName | String | 附件名称。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| 名称 | String | 将在显示注释时使用图标的名称。该值可以是："Graph"、"PushPin"、"Paperclip"、"Tag"。 |
| 不透明度 | Double | 图标的不透明度范围为 0 到 1：0 - 完全透明，1 - 完全不透明。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


