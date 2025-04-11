---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Ajoute des pages choisies à partir d'un tableau de documents dans portStreams. Le document résultant inclut firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage
type: docs
weight: 250
url: /fr/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Ajoute des pages, qui sont choisies à partir d'un tableau de documents dans portStreams. Le document résultant inclut firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux Pdf d'entrée. |
| portStreams | Stream[] | Documents à partir desquels copier des pages. |
| startPage | Int32 | La page commence dans les documents portStreams. |
| endPage | Int32 | La page se termine dans les documents portStreams. |
| outputStream | Stream | Flux Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Ajoute des pages, qui sont choisies à partir des documents portFiles. Le document résultant inclut firstInputFile et toutes les pages des documents portFiles dans la plage startPage à endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf d'entrée. |
| portFiles | String[] | Documents à partir desquels copier des pages. |
| startPage | Int32 | La page commence dans les documents portFiles. |
| endPage | Int32 | La page se termine dans les documents portFiles. |
| outputFile | String | Document Pdf de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Ajoute des pages, qui sont choisies à partir de portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf d'entrée. |
| portFile | String | Pages du fichier Pdf. |
| startPage | Int32 | La page commence dans portFile. |
| endPage | Int32 | La page se termine dans portFile. |
| outputFile | String | Document Pdf de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Ajoute des pages, qui sont choisies à partir de portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de fichier d'entrée. |
| portStream | Stream | Pages du flux de fichier Pdf. |
| startPage | Int32 | La page commence dans le flux de portFile. |
| endPage | Int32 | La page se termine dans le flux de portFile. |
| outputStream | Stream | Flux de fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)