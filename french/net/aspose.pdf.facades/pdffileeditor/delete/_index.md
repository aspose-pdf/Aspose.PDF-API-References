---
title: "PdfFileEditor.Delete"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée et les enregistre comme un nouveau fichier Pdf."
type: docs
weight: 270
url: /fr/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis enregistre un nouveau fichier Pdf.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier d'entrée. |
| pageNumber | Int32[] | Indice de la page du fichier d'entrée. |
| outputFile | String | Chemin du fichier de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis enregistre un nouveau fichier Pdf.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier d'entrée. |
| pageNumber | Int32[] | Indice de la page du fichier d'entrée. |
| outputStream | Stream | Flux du fichier de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


