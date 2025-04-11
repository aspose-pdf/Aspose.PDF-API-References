---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Estrae pagine da file di input e salva come un nuovo file Pdf
type: docs
weight: 410
url: /it/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Estrae pagine dal file di input, salva come un nuovo file Pdf.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file Pdf di input. |
| startPage | Int32 | Numero della pagina di inizio. |
| endPage | Int32 | Numero della pagina di fine. |
| outputFile | String | Percorso del file Pdf di output. |

### Valore di Ritorno

True per successo, o false.

## Osservazioni

Il metodo TryExtract è simile al metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Estrae pagine specificate da un array di numeri, salva come un nuovo file PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di input. |
| pageNumber | Int32[] | Indice della pagina dal file di input. |
| outputFile | String | Percorso del file di output. |

### Valore di Ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryExtract è simile al metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Estrae pagine specificate da un array di numeri, salva come un nuovo file Pdf.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del file di input. |
| pageNumber | Int32[] | Indice della pagina dal file di input. |
| outputStream | Stream | Stream del file di output. |

### Valore di Ritorno

True per successo, o false.

## Osservazioni

Il metodo TryExtract è simile al metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Estrae le pagine specificate dal file sorgente e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream del documento sorgente. |
| pageNumber | Int32[] | Array dei numeri di pagina che verranno estratti. |
| response | HttpResponse | Oggetto HttpResponse dove verrà memorizzato il risultato. |

### Valore di Ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryExtract è simile al metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione fallisce.

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Estrae le pagine specificate dal file sorgente e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file sorgente. |
| pageNumber | Int32[] | Array dei numeri di pagina che verranno estratti. |
| response | HttpResponse | Oggetto HttpResponse dove verrà memorizzato il risultato. |

### Valore di Ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryExtract è simile al metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione fallisce.

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)