---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Concatène deux fichiers
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

La méthode TryConcatenate est semblable à la méthode Concatenate, sauf que la méthode TryConcatenate ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Concatène des documents.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| src | Document[] | Tableau de documents source. |
| dest | Document | Document de destination. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est semblable à la méthode Concatenate, sauf que la méthode TryConcatenate ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [Document](../../../aspose.pdf/document/)
* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Concatène des fichiers en un seul fichier.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Tableau de fichiers à concaténer. |
| outputFile | String | Nom du fichier de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est semblable à la méthode Concatenate, sauf que la méthode TryConcatenate ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatène des fichiers

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | Tableau de flux à concaténer. |
| outputStream | Stream | Flux où le fichier résultat sera stocké. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est semblable à la méthode Concatenate, sauf que la méthode TryConcatenate ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages blanches. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, page blanche, p5, page blanche.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputFile | String | Premier fichier. |
| secInputFile | String | Deuxième fichier. |
| blankPageFile | String | Fichier PDF avec une page blanche. |
| outputFile | String | Fichier résultat. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est semblable à la méthode Concatenate, sauf que la méthode TryConcatenate ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages blanches. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, page blanche, p5, page blanche.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | Le premier flux Pdf. |
| secInputStream | Stream | Le deuxième flux Pdf. |
| blankPageStream | Stream | Le flux Pdf avec une page blanche. |
| outputStream | Stream | Flux Pdf de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est semblable à la méthode Concatenate, sauf que la méthode TryConcatenate ne lance pas d'exception si l'opération échoue.

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

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Concatène des fichiers et enregistre le résultat dans l'objet HttpResponse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Tableau de fichiers à concaténer. |
| response | HttpResponse | Objet de réponse. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est semblable à la méthode Concatenate, sauf que la méthode TryConcatenate ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Concatène des fichiers et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | Tableau de flux contenant des fichiers à concaténer. |
| response | HttpResponse | Objet de réponse. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryConcatenate est semblable à la méthode Concatenate, sauf que la méthode TryConcatenate ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)