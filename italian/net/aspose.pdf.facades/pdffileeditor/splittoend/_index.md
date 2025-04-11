---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Spartisce dal punto di location e salva la parte posteriore in un nuovo file.
type: docs
weight: 360
url: /it/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Divide dalla posizione specificata e salva la parte posteriore come un nuovo file Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del file Pdf sorgente. |
| location | Int32 | La posizione di divisione. |
| outputStream | Stream | Stream del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

I flussi NON vengono chiusi dopo questa operazione a meno che non venga specificato CloseConcatedStreams.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Divide dalla posizione e salva la parte posteriore come un nuovo file.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf sorgente. |
| location | Int32 | La posizione di divisione. |
| outputFile | String | Percorso del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Divide dalla posizione specificata e salva la parte posteriore come un nuovo file Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del file Pdf sorgente. |
| location | Int32 | La posizione di divisione. |
| outputStream | Stream | Stream del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

I flussi NON vengono chiusi dopo questa operazione a meno che non venga specificato CloseConcatedStreams.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)