---
title: Delete
second_title: Aspose.PDF per .NET API Reference
description: Elimina le pagine specificate dallarray di numeri dal file di input salva come un nuovo file Pdf.
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_2}

Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Inserisci il percorso del file. |
| pageNumber | Int32[] | Indice della pagina fuori dal file di input. |
| outputFile | String | Percorso del file di output. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | File di input Flusso. |
| pageNumber | Int32[] | Indice della pagina fuori dal file di input. |
| outputStream | Stream | Flusso di file di output. |

### Valore di ritorno

Vero per il successo o falso.

### Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Delete(string, int[], HttpResponse) {#delete_3}

Elimina le pagine specificate dal documento e memorizza il risultato nell'oggetto HttpResponse.

```csharp
public bool Delete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di origine. |
| pageNumber | Int32[] | Matrice di numeri di pagina che devono essere eliminati. |
| response | HttpResponse | Oggetto di risposta in cui verrà archiviato il documento del risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## Delete(Stream, int[], HttpResponse) {#delete_1}

Elimina le pagine specificate dal documento e salva il risultato nell'oggetto HttpResponse.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso di documenti di origine. |
| pageNumber | Int32[] | Matrice di numeri di pagina che verranno eliminati. |
| response | HttpResponse | Oggetto HTTPResponse |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->