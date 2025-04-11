---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。ファイル添付注釈を作成します。
type: docs
weight: 150
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

ファイル添付注釈を作成します。

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈の矩形。 |
| contents | String | 注釈の内容。 |
| filePath | String | 添付されるファイルのパス。 |
| page | Int32 | 注釈が作成される元のページの番号。 |
| name | String | 注釈を表示する際に使用されるアイコンの名前。この値は次のいずれかです: "Graph", "PushPin", "Paperclip", "Tag". |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### 参照

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

ファイル添付注釈を作成します。

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈の矩形。 |
| contents | String | 注釈の内容。 |
| filePath | String | 添付されるファイルのパス。 |
| page | Int32 | 注釈が作成される元のページの番号。 |
| name | String | 注釈を表示する際に使用されるアイコンの名前。この値は次のいずれかです: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | アイコンの不透明度は0から1の範囲: 0 - 完全に透明、1 - 完全に不透明。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### 参照

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

ファイル添付注釈を作成します。

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈の矩形。 |
| contents | String | 注釈の内容。 |
| attachmentStream | Stream | 添付ファイルのストリーム。 |
| attachmentName | String | 添付ファイルの名前。 |
| page | Int32 | 注釈が作成される元のページの番号。 |
| name | String | 注釈を表示する際に使用されるアイコンの名前。この値は次のいずれかです: "Graph", "PushPin", "Paperclip", "Tag". |

## 例

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

### 参照

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

ファイル添付注釈を作成します。

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈の矩形。 |
| contents | String | 注釈の内容。 |
| attachmentStream | Stream | 添付ファイルのストリーム。 |
| attachmentName | String | 添付ファイルの名前。 |
| page | Int32 | 注釈が作成される元のページの番号。 |
| name | String | 注釈を表示する際に使用されるアイコンの名前。この値は次のいずれかです: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | アイコンの不透明度は0から1の範囲: 0 - 完全に透明、1 - 完全に不透明。 |

## 例

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

### 参照

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)