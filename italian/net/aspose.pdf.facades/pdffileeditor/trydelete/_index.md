---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Elimina le pagine specificate dall'array di numeri dal file di input e salva come un nuovo file Pdf
type: docs
weight: 400
url: /it/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Percorso del file di input. |
| pageNumber | Int32[] | Indice della pagina nel file di input. |
| outputFile | String | Percorso del file di output. |

### Return Value

true se l'operazione è completata con successo; altrimenti, false.

## Remarks

Il metodo TryDelete è simile al metodo Delete, tranne per il fatto che il metodo TryDelete non genera un'eccezione se l'operazione fallisce.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream del file di input. |
| pageNumber | Int32[] | Indice della pagina nel file di input. |
| outputStream | Stream | Stream del file di output. |

### Return Value

True per successo, o false.

## Remarks

Il metodo TryDelete è simile al metodo Delete, tranne per il fatto che il metodo TryDelete non genera un'eccezione se l'operazione fallisce.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Elimina le pagine specificate dal documento e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Percorso del file sorgente. |
| pageNumber | Int32[] | Array dei numeri di pagina che devono essere eliminati. |
| response | HttpResponse | Oggetto di risposta dove il documento risultante sarà memorizzato. |

### Return Value

true se l'operazione è completata con successo; altrimenti, false.

## Remarks

Il metodo TryDelete è simile al metodo Delete, tranne per il fatto che il metodo TryDelete non genera un'eccezione se l'operazione fallisce.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Elimina le pagine specificate dal documento e salva il risultato nell'oggetto HttpResponse.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream del documento sorgente. |
| pageNumber | Int32[] | Array dei numeri di pagina che saranno eliminati. |
| response | HttpResponse | Oggetto HttpResponse |

### Return Value

true se l'operazione è completata con successo; altrimenti, false.

## Remarks

Il metodo TryDelete è simile al metodo Delete, tranne per il fatto che il metodo TryDelete non genera un'eccezione se l'operazione fallisce.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)