---
title: TryMakeNUp
second_title: Référence de l'API Aspose.PDF pour .NET
description: Crée un document N-up et stocke le résultat dans lobjet HttpResponse.
type: docs
weight: 470
url: /fr/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, int, int, PageSize, HttpResponse) {#trymakenup_6}

Crée un document N-up et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Chemin d'accès au fichier source. |
| x | Int32 | Le nombre de colonnes. |
| y | Int32 | Nombre de rangées. |
| pageSize | PageSize | Taille de la page dans le fichier de résultats. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Crée un document N-up et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de document source. |
| x | Int32 | Le nombre de colonnes. |
| y | Int32 | Nombre de rangées. |
| pageSize | PageSize | Taille de la page dans le fichier de résultats. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Crée un document N-up et stocke le résultat dans HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Nom du fichier source. |
| x | Int32 | Le nombre de colonnes. |
| y | Int32 | Nombre de rangées. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Crée un document N-up et stocke le résultat dans HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de document d'entrée. |
| x | Int32 | Le nombre de colonnes. |
| y | Int32 | Nombre de rangées. |
| response | HttpResponse | HttpResponse où le résultat sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Crée un document N-Up du premier fichier d'entrée au fichier de sortie.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin et le nom du fichier pdf. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup_2}

Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée pdf. |
| outputStream | Stream | Flux de sortie pdf. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_3}

Crée un document N-Up du premier flux d'entrée au flux de sortie.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée pdf. |
| outputStream | Stream | Flux de sortie pdf. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_10}

Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page du premier fichier d'entrée et une autre du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputFile | String | premier fichier d'entrée. |
| secondInputFile | String | deuxième fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon faux

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_4}

Crée un document N-Up à partir des deux flux PDF d'entrée vers outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputStream | Stream | premier flux d'entrée. |
| secondInputStream | Stream | deuxième flux d'entrée. |
| outputStream | Stream | Flux de sortie pdf. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon faux

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_11}

Crée un document N-Up à partir des fichiers PDF multi-entrées vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont combinées avec des pages dans les fichiers d'entrée du même numéro de page. Les pages multiples empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFiles | String[] | Fichiers PDF d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| isSidewise | Boolean | Chemin empilé, vrai pour horizontalement et faux pour verticalement. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_5}

Crée un document N-Up à partir des flux PDF multi-entrées vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont combinées avec des pages dans les flux d'entrée du même numéro de page. Les multi-pages empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStreams | Stream[] | Flux d'entrée PDF. |
| outputStream | Stream | Flux de sortie pdf. |
| isSidewise | Boolean | Chemin empilé, vrai pour horizontalement et faux pour verticalement. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_9}

Crée un document N-Up du fichier d'entrée au fichier de sortie.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin et le nom du fichier pdf. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
