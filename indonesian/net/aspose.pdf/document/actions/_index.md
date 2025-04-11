---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Properti dokumen. Mendapatkan tindakan dokumen. Properti ini adalah instance dari kelas DocumentActions yang memungkinkan untuk mendapatkan/mengatur tindakan BeforClosing, BeforSaving, dll.
type: docs
weight: 30
url: /id/net/aspose.pdf/document/actions/
---
## Properti Document.Actions

Mendapatkan tindakan dokumen. Properti ini adalah instance dari kelas DocumentActions yang memungkinkan untuk mendapatkan/mengatur tindakan BeforClosing, BeforSaving, dll.

```csharp
public DocumentActionCollection Actions { get; }
```

## Contoh

Contoh ini menunjukkan cara untuk mendapatkan tindakan setelah membuka dokumen:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Lihat Juga

* kelas [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)