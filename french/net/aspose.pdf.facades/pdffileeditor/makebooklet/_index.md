---
title: MakeBooklet
second_title: Référence de l'API Aspose.PDF pour .NET
description: Crée un livret du fichier dentrée au fichier de sortie.
type: docs
weight: 330
url: /fr/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_8}

Crée un livret du fichier d'entrée au fichier de sortie.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin et le nom du fichier pdf. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet_2}

Crée un livret du InputStream au outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée pdf. |
| outputStream | Stream | flux de sortie pdf. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_9}

Crée un livret du fichier d'entrée au fichier de sortie.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin et le nom du fichier pdf. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_3}

Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux PDF d'entrée. |
| outputStream | Stream | flux de sortie pdf. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_11}

Crée un livret personnalisé du premier fichier d'entrée au fichier de sortie.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Le fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| leftPages | Int32[] | Les pages de gauche du livret. |
| rightPages | Int32[] | Les bonnes pages du livret. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_5}

Crée un livret personnalisé du premier flux d'entrée au flux de sortie.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Le flux d'entrée. |
| outputStream | Stream | flux de sortie pdf. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les bonnes pages. |

### Return_Value

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_10}

Crée un livret personnalisé du premier fichier d'entrée au fichier de sortie.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_4}

Crée un livret du premier flux d'entrée au flux de sortie.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

boolean - Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
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

Vrai si l'opération a réussi.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Créer un livret à partir d'un fichier PDF et le stocker dans HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de documents d'entrée. |
| pageSize | PageSize | Taille de page souhaitée. |
| leftPages | Int32[] | Tableau de numéros de page qui sera placé à gauche. |
| rightPages | Int32[] | Tableau de numéros de page qui sera placé à droite. |
| response | HttpResponse | Objet HTTPResponse. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageSize | PageSize | Taille de page souhaitée dans le fichier de sortie. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Crée un livret à partir du fichier source et stocke le résultat dans HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de documents d'entrée. |
| pageSize | PageSize | Taille de page souhaitée dans le fichier de sortie. |
| response | HttpResponse | Objet Respose où le résultat sera enregistré. |

### Return_Value

true si le livret a été construit avec succès.

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
