---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Extrait des pages des fichiers d'entrée et les enregistre en tant que nouveau fichier Pdf
type: docs
weight: 410
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Extrait des pages du fichier d'entrée, les enregistre en tant que nouveau fichier Pdf.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier Pdf d'entrée. |
| startPage | Int32 | Numéro de la page de départ. |
| endPage | Int32 | Numéro de la page de fin. |
| outputFile | String | Chemin du fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Extrait des pages spécifiées par un tableau de numéros, les enregistre en tant que nouveau fichier PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier d'entrée. |
| pageNumber | Int32[] | Index de la page dans le fichier d'entrée. |
| outputFile | String | Chemin du fichier de sortie. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extrait des pages spécifiées par un tableau de numéros, les enregistre en tant que nouveau fichier Pdf.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier d'entrée. |
| pageNumber | Int32[] | Index de la page dans le fichier d'entrée. |
| outputStream | Stream | Flux du fichier de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du document source. |
| pageNumber | Int32[] | Tableau des numéros de page qui seront extraits. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageNumber | Int32[] | Tableau des numéros de page qui seront extraits. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)