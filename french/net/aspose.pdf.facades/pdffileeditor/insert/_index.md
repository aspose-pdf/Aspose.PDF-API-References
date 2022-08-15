---
title: Insert
second_title: Référence de l'API Aspose.PDF pour .NET
description: Insère des pages dun autre fichier dans le fichier PDF à une position.
type: docs
weight: 320
url: /fr/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_3}

Insère des pages d'un autre fichier dans le fichier PDF à une position.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Saisir le fichier Pdf. |
| insertLocation | Int32 | Position dans le fichier d'entrée. |
| portFile | String | Le fichier Pdf de portage. |
| startPage | Int32 | Position de départ dans portFile. |
| endPage | Int32 | Position finale dans portFile. |
| outputFile | String | Fichier PDF de sortie. |

### Return_Value

Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée du fichier Pdf. |
| insertLocation | Int32 | Insérer la position dans le fichier d'entrée. |
| portStream | Stream | Flux de fichier Pdf pour les pages. |
| startPage | Int32 | A partir de quelle page commencer. |
| endPage | Int32 | À quelle page terminer. |
| outputStream | Stream | Flux de sortie. |

### Return_Value

Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_4}

Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Saisir le fichier Pdf. |
| insertLocation | Int32 | Insérer la position dans le fichier d'entrée. |
| portFile | String | Pages du fichier Pdf. |
| pageNumber | Int32[] | Le numéro de page du fichier porté dans portFile. |
| outputFile | String | Fichier PDF de sortie. |

### Return_Value

Vrai pour le succès, ou faux.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée du fichier Pdf. |
| insertLocation | Int32 | Insérer la position dans le fichier d'entrée. |
| portStream | Stream | Flux de fichier Pdf pour les pages. |
| pageNumber | Int32[] | Le numéro de page du fichier porté dans portFile. |
| outputStream | Stream | Flux de sortie. |

### Return_Value

Vrai si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], HttpResponse) {#insert_5}

Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Nom du fichier source. |
| insertLocation | Int32 | Numéro de page où le deuxième fichier sera inséré. |
| portFile | String | Chemin du fichier qui sera inséré. |
| pageNumber | Int32[] | Tableau de numéros de page dans le fichier source qui sera inséré. |
| response | HttpResponse | Objet de réponse où le résultat sera stocké. |

### Return_Value

vrai de l'insertion a réussi.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], HttpResponse) {#insert_2}

Insère le document dans un autre document et stocke le résultat dans l'objet de réponse.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Diffuser avec le document source |
| insertLocation | Int32 | Emplacement où un autre document sera inséré. |
| portStream | Stream | Document à insérer. |
| pageNumber | Int32[] | Tableau des numéros de page dans le deuxième document qui sera inséré. |
| response | HttpResponse | Objet de réponse où le résultat sera stocké. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
