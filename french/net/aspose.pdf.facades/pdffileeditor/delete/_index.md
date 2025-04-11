---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée et enregistre en tant que nouveau fichier Pdf
type: docs
weight: 270
url: /fr/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre en tant que nouveau fichier Pdf.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier d'entrée. |
| pageNumber | Int32[] | Index de la page dans le fichier d'entrée. |
| outputFile | String | Chemin du fichier de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre en tant que nouveau fichier Pdf.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier d'entrée. |
| pageNumber | Int32[] | Index de la page dans le fichier d'entrée. |
| outputStream | Stream | Flux du fichier de sortie. |

### Valeur de retour

Vrai pour succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)