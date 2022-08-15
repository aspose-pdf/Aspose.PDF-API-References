---
title: TryConcatenate
second_title: Référence de l'API Aspose.PDF pour .NET
description: Concatène deux fichiers.
type: docs
weight: 420
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_4}

Concatène deux fichiers.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputFile | String | Premier fichier à concaténer. |
| secInputFile | String | Deuxième fichier à concaténer. |
| outputFile | String | Fichier de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Concatène des documents.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| src | Document[] | Tableau de documents sources. |
| dest | Document | Document de destination. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryConcatenate est comme la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Voir également

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_6}

Concatène les fichiers en un seul fichier.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFiles | String[] | Tableau de fichiers à concaténer. |
| outputFile | String | Nom du fichier de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryConcatenate est comme la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatène les fichiers

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream[] | Tableau de flux à concaténer. |
| outputStream | Stream | Flux où le fichier de résultats sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryConcatenate est comme la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_5}

Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vierges. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputFile | String | Premier dossier. |
| secInputFile | String | Deuxième dossier. |
| blankPageFile | String | Fichier PDF avec page vierge. |
| outputFile | String | Fichier de résultat. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate , sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vierges. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputStream | Stream | Le premier flux PDF. |
| secInputStream | Stream | Le deuxième flux PDF. |
| blankPageStream | Stream | Le Flux Pdf avec page vierge. |
| outputStream | Stream | Flux de sortie PDF. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate , sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Concatène les fichiers et enregistre le résultat dans l'objet HttpResposnse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFiles | String[] | Tableau de fichiers à concaténer. |
| response | HttpResponse | Objet de réponse. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Concatène les fichiers et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream[] | Tableau de flux contenant les fichiers à concaténer. |
| response | HttpResponse | Objet de réponse/ |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
