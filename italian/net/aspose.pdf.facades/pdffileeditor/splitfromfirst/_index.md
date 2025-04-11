---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Divide il file Pdf dalla prima pagina alla posizione specificata e salva la parte anteriore come un nuovo file
type: docs
weight: 340
url: /it/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Divide il file Pdf dalla prima pagina alla posizione specificata e salva la parte anteriore come un nuovo file.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf sorgente. |
| location | Int32 | Il punto di divisione. |
| outputFile | String | File Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Divide dall'inizio alla posizione specificata e salva la parte anteriore nello Stream di output.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del file Pdf sorgente. |
| location | Int32 | Il punto di divisione. |
| outputStream | Stream | Stream del file di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Gli stream NON vengono chiusi dopo questa operazione.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)