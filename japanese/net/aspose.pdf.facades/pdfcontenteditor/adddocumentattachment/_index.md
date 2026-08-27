---
title: "PdfContentEditor.AddDocumentAttachment"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。注釈なしでドキュメント添付を追加します。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

注釈なしでドキュメント添付ファイルを追加します。

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fileAttachmentPath | String | 添付されるファイルのパスです。 |
| 説明 | String | 説明情報です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

注釈なしでドキュメント添付ファイルを追加します。

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fileAttachmentStream | Stream | ファイルのストリームが添付されます。 |
| fileAttachmentName | String | 添付ファイル名です。 |
| 説明 | String | 説明情報です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


