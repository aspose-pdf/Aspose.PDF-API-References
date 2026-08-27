---
title: "PdfFileEditor.CorruptedItems"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-egenskapen. Array av uppkomna problem när sammanslagning utfördes. För varje korrupt Document som skickas till Concatenate-funktionen skapas en ny CorruptedItem-post. Denna egenskap får endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted."
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

Array av påträffade problem när konkatenering utfördes. För varje korrupt dokument som skickas till Concatenate()-funktionen skapas en ny CorruptedItem-post. Denna egenskap kan endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted.

```csharp
//sammanfoga Document och visa information om korrupta Document
PdfFileEditor pfe = new PdfFileEditor();
pfe.CorruptedFileAction = PdfFileEditor.ConcatenateCorruptedFileActions.ConcatenateIgnoringCorrupted;
if (pfe.CorruptedItems.Length >0)
{
  foreach(PdfFileEditor.CorruptedItem item in pfe.CorruptedItems)
  {
     Console.WriteLine(item.Index + " reason: " + item.Exception);
  }
}
```

```csharp
public CorruptedItem[] CorruptedItems { get; }
```

### Se även

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


