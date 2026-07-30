---
title: "PdfFileEditor.TryInsert"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Insère des pages d'un autre fichier dans le fichier Pdf d'entrée"
type: docs
weight: 420
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Insère des pages d'un autre fichier dans le fichier Pdf d'entrée.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf d'entrée. |
| insertLocation | Int32 | Insérer la position dans le fichier d'entrée. |
| portFile | String | Pages du fichier Pdf. |
| pageNumber | Int32[] | Le numéro de page du portage dans portFile. |
| outputFile | String | Fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryInsert est similaire à la méthode Insert, sauf que la méthode TryInsert ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Insère des pages d'un autre fichier dans le fichier Pdf d'entrée.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée du fichier Pdf. |
| insertLocation | Int32 | Insérer la position dans le fichier d'entrée. |
| portStream | Stream | Flux du fichier Pdf pour les pages. |
| pageNumber | Int32[] | Le numéro de page du portage dans portFile. |
| outputStream | Stream | Flux de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryInsert est similaire à la méthode Insert, sauf que la méthode TryInsert ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


