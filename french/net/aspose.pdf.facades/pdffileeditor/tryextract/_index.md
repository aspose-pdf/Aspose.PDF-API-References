---
title: "PdfFileEditor.TryExtract"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Extrait les pages du fichier d'entrée et les enregistre comme un nouveau fichier Pdf."
type: docs
weight: 410
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Extrait les pages du fichier d'entrée, puis enregistre un nouveau fichier Pdf.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier Pdf d'entrée. |
| startPage | Int32 | Numéro de page de début. |
| endPage | Int32 | Numéro de page de fin. |
| outputFile | String | Chemin du fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Extrait les pages spécifiées par un tableau de numéros, puis enregistre un nouveau fichier PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier d'entrée. |
| pageNumber | Int32[] | Indice de la page du fichier d'entrée. |
| outputFile | String | Chemin du fichier de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extrait les pages spécifiées par un tableau de numéros, puis enregistre un nouveau fichier Pdf.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier d'entrée. |
| pageNumber | Int32[] | Indice de la page du fichier d'entrée. |
| outputStream | Stream | Flux du fichier de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryExtract est similaire à la méthode Extract, sauf que la méthode TryExtract ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


