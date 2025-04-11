---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Divide dalla posizione e salva la parte posteriore come un nuovo file
type: docs
weight: 470
url: /it/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Divide dalla posizione e salva la parte posteriore come un nuovo file.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf sorgente. |
| location | Int32 | La posizione di divisione. |
| outputFile | String | Percorso del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Il metodo TrySplitToEnd è simile al metodo SplitToEnd, tranne per il fatto che il metodo TrySplitToEnd non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Divide dalla posizione specificata e salva la parte posteriore come un nuovo file Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del file Pdf sorgente. |
| location | Int32 | La posizione di divisione. |
| outputStream | Stream | Stream del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Osservazioni

Gli stream NON vengono chiusi dopo questa operazione a meno che non venga specificato CloseConcatedStreams. Il metodo TrySplitToEnd è simile al metodo SplitToEnd, tranne per il fatto che il metodo TrySplitToEnd non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Divide dalla posizione specificata e salva la parte posteriore nell'oggetto HttpResponse.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del documento sorgente. |
| location | Int32 | Punto di divisione. |
| response | HttpResponse | Oggetto HttpResponse. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TrySplitToEnd è simile al metodo SplitToEnd, tranne per il fatto che il metodo TrySplitToEnd non genera un'eccezione se l'operazione fallisce.

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Divide dalla posizione specificata e salva la parte posteriore nell'oggetto HttpResponse.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | nome del file sorgente. |
| location | Int32 | Punto di divisione. |
| response | HttpResponse | Oggetti HttpResponse. |

### Valore di ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TrySplitToEnd è simile al metodo SplitToEnd, tranne per il fatto che il metodo TrySplitToEnd non genera un'eccezione se l'operazione fallisce.

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)