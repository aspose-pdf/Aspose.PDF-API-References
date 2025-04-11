---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Inserisce pagine da un altro file nel file Pdf in una posizione
type: docs
weight: 290
url: /it/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Inserisce pagine da un altro file nel file Pdf in una posizione.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf di input. |
| insertLocation | Int32 | Posizione nel file di input. |
| portFile | String | Il file Pdf di porting. |
| startPage | Int32 | Posizione di partenza in portFile. |
| endPage | Int32 | Posizione finale in portFile. |
| outputFile | String | File Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Inserisce pagine da un altro file nel file Pdf di input.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream di input del file Pdf. |
| insertLocation | Int32 | Posizione di inserimento nel file di input. |
| portStream | Stream | Stream del file Pdf per le pagine. |
| startPage | Int32 | Da quale pagina iniziare. |
| endPage | Int32 | A quale pagina finire. |
| outputStream | Stream | Stream di output. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Inserisce pagine da un altro file nel file Pdf di input.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File Pdf di input. |
| insertLocation | Int32 | Posizione di inserimento nel file di input. |
| portFile | String | Pagine dal file Pdf. |
| pageNumber | Int32[] | Il numero di pagina del portato in portFile. |
| outputFile | String | File Pdf di output. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Inserisce pagine da un altro file nel file Pdf di input.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream di input del file Pdf. |
| insertLocation | Int32 | Posizione di inserimento nel file di input. |
| portStream | Stream | Stream del file Pdf per le pagine. |
| pageNumber | Int32[] | Il numero di pagina del portato in portFile. |
| outputStream | Stream | Stream di output. |

### Valore di ritorno

True se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)