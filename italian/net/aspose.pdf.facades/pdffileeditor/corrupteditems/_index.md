---
title: "PdfFileEditor.CorruptedItems"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà PdfFileEditor. Array di problemi riscontrati quando è stata eseguita la concatenazione. Per ogni Document corrotto passato alla funzione Concatenate viene creata una nuova voce CorruptedItem. Questa proprietà può essere usata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted"
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

Array dei problemi riscontrati durante l'esecuzione della concatenazione. Per ogni documento corrotto passato alla funzione Concatenate() viene creata una nuova voce CorruptedItem. Questa proprietà può essere usata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted.

```csharp
//concatenare i Document e mostrare le informazioni sui Document corrotti
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

### Vedi anche

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


