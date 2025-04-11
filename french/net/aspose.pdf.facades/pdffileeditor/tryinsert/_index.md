---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Insère des pages d'un autre fichier dans le fichier Pdf d'entrée
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
| insertLocation | Int32 | Position d'insertion dans le fichier d'entrée. |
| portFile | String | Pages du fichier Pdf. |
| pageNumber | Int32[] | Le numéro de page du fichier porté dans portFile. |
| outputFile | String | Fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TryInsert est comme la méthode Insert, sauf que la méthode TryInsert ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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
| insertLocation | Int32 | Position d'insertion dans le fichier d'entrée. |
| portStream | Stream | Flux du fichier Pdf pour les pages. |
| pageNumber | Int32[] | Le numéro de page du fichier porté dans portFile. |
| outputStream | Stream | Flux de sortie. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryInsert est comme la méthode Insert, sauf que la méthode TryInsert ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Nom du fichier source. |
| insertLocation | Int32 | Numéro de page où le deuxième fichier sera inséré. |
| portFile | String | Chemin vers le fichier qui sera inséré. |
| pageNumber | Int32[] | Tableau des numéros de page dans le fichier source qui seront insérés. |
| response | HttpResponse | Objet de réponse où le résultat sera stocké. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryInsert est comme la méthode Insert, sauf que la méthode TryInsert ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Insère un document dans un autre document et stocke le résultat dans l'objet de réponse.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux avec le document source |
| insertLocation | Int32 | Emplacement où l'autre document sera inséré. |
| portStream | Stream | Document à insérer. |
| pageNumber | Int32[] | Tableau des numéros de page dans le deuxième document qui seront insérés. |
| response | HttpResponse | Objet de réponse où le résultat sera stocké. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TryInsert est comme la méthode Insert, sauf que la méthode TryInsert ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)