---
title: TryInsert
second_title: Référence de l'API Aspose.PDF pour .NET
description: Insère des pages dun autre fichier dans le fichier PDF dentrée.
type: docs
weight: 450
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_2}

Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

### Remarques

La méthode TryInsert est similaire à la méthode Insert, sauf que la méthode TryInsert ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryInsert est similaire à la méthode Insert, sauf que la méthode TryInsert ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryInsert est similaire à la méthode Insert, sauf que la méthode TryInsert ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Insère le document dans un autre document et stocke le résultat dans l'objet de réponse.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryInsert est similaire à la méthode Insert, sauf que la méthode TryInsert ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
