---
title: "PdfFileEditor.TryDelete"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée et les enregistre comme un nouveau fichier Pdf."
type: docs
weight: 400
url: /fr/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis enregistre un nouveau fichier Pdf.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier d'entrée. |
| pageNumber | Int32[] | Indice de la page du fichier d'entrée. |
| outputFile | String | Chemin du fichier de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryDelete est similaire à la méthode Delete, sauf que la méthode TryDelete ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis enregistre un nouveau fichier Pdf.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier d'entrée. |
| pageNumber | Int32[] | Indice de la page du fichier d'entrée. |
| outputStream | Stream | Flux du fichier de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryDelete est similaire à la méthode Delete, sauf que la méthode TryDelete ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


