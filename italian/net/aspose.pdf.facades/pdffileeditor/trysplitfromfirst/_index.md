---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Divide il file Pdf dalla prima pagina alla posizione specificata e salva la parte anteriore come un nuovo file
type: docs
weight: 460
url: /it/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Divide il file Pdf dalla prima pagina alla posizione specificata e salva la parte anteriore come un nuovo file.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | File Pdf sorgente. |
| location | Int32 | Il punto di divisione. |
| outputFile | String | File Pdf di output. |

### Return Value

True per successo, o false.

## Remarks

Il metodo TrySplitFromFirst è simile al metodo SplitFromFirst, tranne per il fatto che il metodo TrySplitFromFirst non genera un'eccezione se l'operazione fallisce.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Divide dalla partenza alla posizione specificata e salva la parte anteriore nello Stream di output.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream del file Pdf sorgente. |
| location | Int32 | Il punto di divisione. |
| outputStream | Stream | Stream del file di output. |

### Return Value

True per successo, o false.

## Remarks

Gli stream NON vengono chiusi dopo questa operazione. Il metodo TrySplitFromFirst è simile al metodo SplitFromFirst, tranne per il fatto che il metodo TrySplitFromFirst non genera un'eccezione se l'operazione fallisce.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Divide il documento dalla prima pagina alla posizione e salva il risultato negli oggetti HttpResponse.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Nome del file sorgente. |
| location | Int32 | Punto di divisione. |
| response | HttpResponse | Oggetti HttpResponse. |

### Return Value

true se l'operazione è completata con successo; altrimenti, false.

## Remarks

Il metodo TrySplitFromFirst è simile al metodo SplitFromFirst, tranne per il fatto che il metodo TrySplitFromFirst non genera un'eccezione se l'operazione fallisce.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Divide il documento dalla partenza alla posizione specificata e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream del documento sorgente. |
| location | Int32 | Il punto di divisione. |
| response | HttpResponse | Oggetto HttpResponse dove verrà memorizzato il risultato. |

### Return Value

true se l'operazione è completata con successo; altrimenti, false.

## Remarks

Il metodo TrySplitFromFirst è simile al metodo SplitFromFirst, tranne per il fatto che il metodo TrySplitFromFirst non genera un'eccezione se l'operazione fallisce.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)