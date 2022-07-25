---
title: MakeNUp
second_title: Référence de l'API Aspose.PDF pour .NET
description: Crée un document N-Up du premier fichier dentrée au fichier de sortie.
type: docs
weight: 340
url: /fr/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(string, string, int, int) {#makenup_8}

Crée un document N-Up du premier fichier d'entrée au fichier de sortie.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin et le nom du fichier pdf. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée pdf. |
| outputStream | Stream | Flux de sortie pdf. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Crée un document N-Up du premier flux d'entrée au flux de sortie.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée pdf. |
| outputStream | Stream | Flux de sortie pdf. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page du premier fichier d'entrée et une autre du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputFile | String | premier fichier d'entrée. |
| secondInputFile | String | deuxième fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Crée un document N-Up à partir des deux flux PDF d'entrée vers outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstInputStream | Stream | premier flux d'entrée. |
| secondInputStream | Stream | deuxième flux d'entrée. |
| outputStream | Stream | Flux de sortie pdf. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_11}

Crée un document N-Up à partir des fichiers PDF multi-entrées vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont combinées avec des pages dans les fichiers d'entrée du même numéro de page. Les pages multiples empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFiles | String[] | Fichiers PDF d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| isSidewise | Boolean | Chemin empilé, vrai pour horizontalement et faux pour verticalement. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_5}

Crée un document N-Up à partir des flux PDF multi-entrées vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont combinées avec des pages dans les flux d'entrée du même numéro de page. Les multi-pages empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStreams | Stream[] | Flux d'entrée PDF. |
| outputStream | Stream | Flux de sortie pdf. |
| isSidewise | Boolean | Chemin empilé, vrai pour horizontalement et faux pour verticalement. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_9}

Crée un document N-Up du fichier d'entrée au fichier de sortie.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin et le nom du fichier pdf. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, PageSize, HttpResponse) {#makenup}

Crée un document N-up et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de document source. |
| x | Int32 | Le nombre de colonnes. |
| y | Int32 | Nombre de rangées. |
| pageSize | PageSize | Taille de la page dans le fichier de résultats. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, PageSize, HttpResponse) {#makenup_6}

Crée un document N-up et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Chemin d'accès au fichier source. |
| x | Int32 | Le nombre de colonnes. |
| y | Int32 | Nombre de rangées. |
| pageSize | PageSize | Taille de la page dans le fichier de résultats. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, HttpResponse) {#makenup_7}

Crée un document N-up et stocke le résultat dans HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Nom du fichier source. |
| x | Int32 | Le nombre de colonnes. |
| y | Int32 | Nombre de rangées. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, HttpResponse) {#makenup_1}

Crée un document N-up et stocke le résultat dans HttpResponse.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de document d'entrée. |
| x | Int32 | Le nombre de colonnes. |
| y | Int32 | Nombre de rangées. |
| response | HttpResponse | HttpResponse où le résultat sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
