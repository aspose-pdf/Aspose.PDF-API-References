---
title: "PdfPageEditor.Save"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfPageEditor. Salva il Document modificato in un file"
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Salva il documento modificato in un file.

```csharp
public override void Save(string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Percorso del file in cui verrà salvato il documento. |

## Esempi

Il seguente esempio dimostra come salvare il documento PDF modificato

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Vedi anche

* class [PdfPageEditor](../)
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
| outputStream | Stream | Stream in cui verrà salvato il documento PDF modificato. |

## Esempi

Il seguente esempio dimostra come salvare il documento PDF modificato in uno stream.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Vedi anche

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


