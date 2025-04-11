---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Insère des pages d'un autre fichier dans le fichier Pdf à une position
type: docs
weight: 290
url: /fr/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Insère des pages d'un autre fichier dans le fichier Pdf à une position.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf d'entrée. |
| insertLocation | Int32 | Position dans le fichier d'entrée. |
| portFile | String | Le fichier Pdf de portage. |
| startPage | Int32 | Position de départ dans portFile. |
| endPage | Int32 | Position de fin dans portFile. |
| outputFile | String | Fichier Pdf de sortie. |

### Valeur de retour

Vrai pour succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Insère des pages d'un autre fichier dans le fichier Pdf d'entrée.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée du fichier Pdf. |
| insertLocation | Int32 | Position d'insertion dans le fichier d'entrée. |
| portStream | Stream | Flux du fichier Pdf pour les pages. |
| startPage | Int32 | À partir de quelle page commencer. |
| endPage | Int32 | À quelle page finir. |
| outputStream | Stream | Flux de sortie. |

### Valeur de retour

Vrai pour succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Insère des pages d'un autre fichier dans le fichier Pdf d'entrée.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

Vrai pour succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Insère des pages d'un autre fichier dans le fichier Pdf d'entrée.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)