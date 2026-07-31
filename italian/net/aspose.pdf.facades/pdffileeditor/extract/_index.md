---
title: "PdfFileEditor.Extract"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Estrae le pagine dal file di input e le salva come un nuovo file Pdf"
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Estrae le pagine dal file di input, salvando come un nuovo file Pdf.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file Pdf di input. |
| startPage | Int32 | Numero della Page iniziale. |
| endPage | Int32 | Numero della Page finale. |
| outputFile | String | Percorso del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Estrae le pagine specificate da un array di numeri, salvando come un nuovo file PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Percorso del file di input. |
| pageNumber | Int32[] | Indice della pagina nel file di input. |
| outputFile | String | Percorso del file di output. |

### Valore di ritorno

True se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Estrae le pagine dal file di input, salvando come un nuovo file Pdf.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del file di input. |
| startPage | Int32 | Numero della Page iniziale. |
| endPage | Int32 | Numero della Page finale. |
| outputStream | Stream | Stream del file Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Estrae le pagine specificate da un array di numeri, salvando come un nuovo file Pdf.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del file di input. |
| pageNumber | Int32[] | Indice della pagina nel file di input. |
| outputStream | Stream | Flusso del file di output. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


