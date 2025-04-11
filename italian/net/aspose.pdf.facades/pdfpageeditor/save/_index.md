---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfPageEditor. Salva il documento modificato nel file
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Salva il documento modificato nel file.

```csharp
public override void Save(string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Percorso del file dove il documento sarà salvato. |

## Esempi

Il seguente esempio dimostra come salvare un documento PDF modificato

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Vedi Anche

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Salva il documento modificato nello stream.

```csharp
public override void Save(Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream dove il documento PDF modificato sarà salvato. |

## Esempi

Il seguente esempio dimostra come salvare un documento PDF modificato nello stream.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Vedi Anche

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)