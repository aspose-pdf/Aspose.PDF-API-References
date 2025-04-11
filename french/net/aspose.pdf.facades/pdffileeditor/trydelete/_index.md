---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée et enregistre en tant que nouveau fichier Pdf
type: docs
weight: 400
url: /fr/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre en tant que nouveau fichier Pdf.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier d'entrée. |
| pageNumber | Int32[] | Index de la page dans le fichier d'entrée. |
| outputFile | String | Chemin du fichier de sortie. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryDelete est semblable à la méthode Delete, sauf que la méthode TryDelete ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre en tant que nouveau fichier Pdf.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier d'entrée. |
| pageNumber | Int32[] | Index de la page dans le fichier d'entrée. |
| outputStream | Stream | Flux du fichier de sortie. |

### Valeur de retour

True pour le succès, ou false.

## Remarques

La méthode TryDelete est semblable à la méthode Delete, sauf que la méthode TryDelete ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Supprime les pages spécifiées du document et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageNumber | Int32[] | Tableau des numéros de pages qui doivent être supprimées. |
| response | HttpResponse | Objet de réponse où le document résultant sera stocké. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryDelete est semblable à la méthode Delete, sauf que la méthode TryDelete ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Supprime les pages spécifiées du document et enregistre le résultat dans l'objet HttpResponse.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du document source. |
| pageNumber | Int32[] | Tableau des numéros de pages qui seront supprimées. |
| response | HttpResponse | Objet HttpResponse |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryDelete est semblable à la méthode Delete, sauf que la méthode TryDelete ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)