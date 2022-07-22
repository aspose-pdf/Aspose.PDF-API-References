---
title: Concatenate
second_title: Référence de l'API Aspose.PDF pour .NET
description: Concatène deux fichiers.
type: docs
weight: 290
url: /fr/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_5}

Concatène deux fichiers.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputFile | String | Premier fichier à concaténer. |
| secInputFile | String | Deuxième fichier à concaténer. |
| outputFile | String | Fichier de sortie. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Concatène deux fichiers.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputStream | Stream | Flux du premier fichier. |
| secInputStream | Stream | Flux du deuxième fichier. |
| outputStream | Stream | Flux où le fichier de résultats sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Concatène des documents.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| src | Document[] | Tableau de documents sources. |
| dest | Document | Document de destination. |

### Return_Value

Vrai si la concaténation a réussi.

### Voir également

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_7}

Concatène les fichiers en un seul fichier.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFiles | String[] | Tableau de fichiers à concaténer. |
| outputFile | String | Nom du fichier de sortie. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Concatène les fichiers

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream[] | Tableau de flux à concaténer. |
| outputStream | Stream | Flux où le fichier de résultats sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_6}

Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vierges. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputFile | String | Premier dossier. |
| secInputFile | String | Deuxième dossier. |
| blankPageFile | String | Fichier PDF avec page vierge. |
| outputFile | String | Fichier de résultat. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vierges. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputStream | Stream | Le premier flux PDF. |
| secInputStream | Stream | Le deuxième flux PDF. |
| blankPageStream | Stream | Le Flux Pdf avec page vierge. |
| outputStream | Stream | Flux de sortie PDF. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Concatenate(string[], HttpResponse) {#concatenate_8}

Concatène les fichiers et enregistre le résultat dans l'objet HttpResposnse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFiles | String[] | Tableau de fichiers à concaténer. |
| response | HttpResponse | Objet de réponse. |

### Return_Value

true si la concaténation a réussi.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Concatène les fichiers et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream[] | Tableau de flux contenant les fichiers à concaténer. |
| response | HttpResponse | Objet de réponse/ |

### Return_Value

true si l'opération a réussi.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
