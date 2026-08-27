---
title: "PdfFileEditor.TryConcatenate"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Concatène deux fichiers"
type: docs
weight: 390
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

Concatène deux fichiers.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputFile | String | Premier fichier à concaténer. |
| secInputFile | String | Deuxième fichier à concaténer. |
| outputFile | String | Fichier de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Concatène les documents.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| src | Document[] | Tableau des documents source. |
| dest | Document | Document de destination. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Concatène les fichiers en un seul fichier.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Tableau des fichiers à concaténer. |
| outputFile | String | Nom du fichier de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatène les fichiers

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | Tableau de flux à concaténer. |
| outputStream | Stream | Flux où le fichier résultant sera stocké. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. par ex. : document1 possède 5 pages : p1, p2, p3, p4, p5. document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputFile | String | Premier fichier. |
| secInputFile | String | Deuxième fichier. |
| blankPageFile | String | Fichier PDF avec page vierge. |
| outputFile | String | Fichier résultat. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. par ex. : document1 possède 5 pages : p1, p2, p3, p4, p5. document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | Le premier flux Pdf. |
| secInputStream | Stream | Le deuxième flux Pdf. |
| blankPageStream | Stream | Le flux Pdf avec page vierge. |
| outputStream | Stream | Flux Pdf de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est similaire à la méthode Concatenate, sauf que la méthode TryConcatenate ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


