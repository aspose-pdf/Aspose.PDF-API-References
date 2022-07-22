---
title: TryExtract
second_title: Référence de l'API Aspose.PDF pour .NET
description: Extrait les pages du fichier dentrée enregistre en tant que nouveau fichier Pdf.
type: docs
weight: 440
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_2}

Extrait les pages du fichier d'entrée, enregistre en tant que nouveau fichier Pdf.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Entrez le chemin du fichier Pdf. |
| startPage | Int32 | Numéro de la page de démarrage. |
| endPage | Int32 | Numéro de page de fin. |
| outputFile | String | Chemin du fichier PDF de sortie. |

### Return_Value

Vrai pour le succès, ou faux.

### Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_3}

Extrait les pages spécifiées par un tableau de nombres, enregistre en tant que nouveau fichier PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Chemin d'accès au fichier d'entrée. |
| pageNumber | Int32[] | Index de page hors du fichier d'entrée. |
| outputFile | String | Chemin du fichier de sortie. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extrait les pages spécifiées par un tableau de nombres, enregistre en tant que nouveau fichier Pdf.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Fichier d'entrée Flux. |
| pageNumber | Int32[] | Index de page hors du fichier d'entrée. |
| outputStream | Stream | Flux de fichiers de sortie. |

### Return_Value

Vrai pour le succès, ou faux.

### Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de document source. |
| pageNumber | Int32[] | Tableau des numéros de page qui seront extraits. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageNumber | Int32[] | Tableau des numéros de page qui seront extraits. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
