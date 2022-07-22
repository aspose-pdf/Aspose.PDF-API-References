---
title: TryMakeBooklet
second_title: Référence de l'API Aspose.PDF pour .NET
description: Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.
type: docs
weight: 460
url: /fr/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, PageSize, int[], int[], HttpResponse) {#trymakebooklet_6}

Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageSize | PageSize | Taille de page souhaitée. |
| leftPages | Int32[] | Tableau des numéros de page à placer à gauche. |
| rightPages | Int32[] | Tableau de numéros de page à placer à droite. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Créer un livret à partir d'un fichier PDF et le stocker dans HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de documents d'entrée. |
| pageSize | PageSize | Taille de page souhaitée. |
| leftPages | Int32[] | Tableau de numéros de page qui sera placé à gauche. |
| rightPages | Int32[] | Tableau de numéros de page qui sera placé à droite. |
| response | HttpResponse | Objet HTTPResponse. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageSize | PageSize | Taille de page souhaitée dans le fichier de sortie. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Crée un livret à partir du fichier source et stocke le résultat dans HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de documents d'entrée. |
| pageSize | PageSize | Taille de page souhaitée dans le fichier de sortie. |
| response | HttpResponse | Objet Respose où le résultat sera enregistré. |

### Return_Value

true si le livret a été construit avec succès.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Crée un livret du fichier d'entrée au fichier de sortie.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin et le nom du fichier pdf. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet_2}

Crée un livret du InputStream au outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée pdf. |
| outputStream | Stream | flux de sortie pdf. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_9}

Crée un livret du fichier d'entrée au fichier de sortie.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin et le nom du fichier pdf. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Return_Value

Vrai si l'opération a réussi.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_3}

Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux PDF d'entrée. |
| outputStream | Stream | flux de sortie pdf. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_11}

Crée un livret personnalisé du premier fichier d'entrée au fichier de sortie.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Le fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| leftPages | Int32[] | Les pages de gauche du livret. |
| rightPages | Int32[] | Les bonnes pages du livret. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_5}

Crée un livret personnalisé du premier flux d'entrée au flux de sortie.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Le flux d'entrée. |
| outputStream | Stream | flux de sortie pdf. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les bonnes pages. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_10}

Crée un livret personnalisé du premier fichier d'entrée au fichier de sortie.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Le fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les bonnes pages. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_4}

Crée un livret du premier flux d'entrée au flux de sortie.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Le flux d'entrée. |
| outputStream | Stream | flux de sortie pdf. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les bonnes pages. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
