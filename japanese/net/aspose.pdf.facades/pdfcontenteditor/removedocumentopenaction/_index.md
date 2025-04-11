---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。ドキュメントからオープンアクションを削除します。この操作は、起動時に明示的な GoTo アクションを使用する複数のドキュメントを連結する際に便利です。
type: docs
weight: 430
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction メソッド

ドキュメントからオープンアクションを削除します。この操作は、起動時に明示的な 'GoTo' アクションを使用する複数のドキュメントを連結する際に便利です。

```csharp
public void RemoveDocumentOpenAction()
```

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)