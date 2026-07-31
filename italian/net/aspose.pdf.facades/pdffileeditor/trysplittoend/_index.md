---
title: "PdfFileEditor.TrySplitToEnd"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Divide a partire da location e salva la parte finale come un nuovo file."
type: docs
weight: 470
url: /it/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Divide dalla posizione e salva la parte posteriore come nuovo file.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf di origine. |
| location | Int32 | La posizione di divisione. |
| outputFile | String | Percorso del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Il metodo TrySplitToEnd è simile al metodo SplitToEnd, tranne che il metodo TrySplitToEnd non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Divide dalla posizione specificata e salva la parte posteriore come nuovo Stream di file.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del file Pdf di origine. |
| location | Int32 | La posizione di divisione. |
| outputStream | Stream | Stream del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Gli stream NON vengono chiusi dopo questa operazione a meno che sia specificato CloseConcatedStreams. Il metodo TrySplitToEnd è simile al metodo SplitToEnd, tranne che il metodo TrySplitToEnd non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


