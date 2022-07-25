---
title: TryExtract
second_title: Aspose.PDF per .NET API Reference
description: Estrae le pagine dal file di input salva come nuovo file Pdf.
type: docs
weight: 440
url: /it/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_2}

Estrae le pagine dal file di input, salva come nuovo file Pdf.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso del file Pdf. |
| startPage | Int32 | Numero di pagina iniziale. |
| endPage | Int32 | Numero di pagina finale. |
| outputFile | String | Percorso del file Pdf di output. |

### Valore di ritorno

Vero per il successo o falso.

### Osservazioni

Il metodo TryExtract è come il metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_3}

Estrae le pagine specificate dall'array di numeri, le salva come un nuovo file PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso del file. |
| pageNumber | Int32[] | Indice della pagina fuori dal file di input. |
| outputFile | String | Percorso del file di output. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryExtract è come il metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Estrae le pagine specificate dall'array di numeri, le salva come un nuovo file Pdf.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | File di input Flusso. |
| pageNumber | Int32[] | Indice della pagina fuori dal file di input. |
| outputStream | Stream | Flusso di file di output. |

### Valore di ritorno

Vero per il successo o falso.

### Osservazioni

Il metodo TryExtract è come il metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del documento di origine. |
| pageNumber | Int32[] | Matrice di numeri di pagina che verranno estratti. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryExtract è come il metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di origine. |
| pageNumber | Int32[] | Matrice di numeri di pagina che verranno estratti. |
| response | HttpResponse | Oggetto HttpResponse in cui verrà archiviato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryExtract è come il metodo Extract, tranne per il fatto che il metodo TryExtract non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
