---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Crée un document NUp à partir de firstInputFile vers outputFile
type: docs
weight: 440
url: /fr/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Crée un document N-up et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin vers le fichier source. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | Taille de la page dans le fichier résultat. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Crée un document N-up et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du document source. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | Taille de la page dans le fichier résultat. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Crée un document N-up et stocke le résultat dans HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Nom du fichier source. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Crée un document N-up et stocke le résultat dans HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du document d'entrée. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| response | HttpResponse | HttpResponse où le résultat sera stocké. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Crée un document N-Up à partir de firstInputFile vers outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux pdf d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux pdf d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Voir aussi

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page provenant du premier fichier d'entrée et une autre provenant du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputFile | String | premier fichier d'entrée. |
| secondInputFile | String | deuxième fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Crée un document N-Up à partir des deux flux PDF d'entrée vers outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | premier flux d'entrée. |
| secondInputStream | Stream | deuxième flux d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Crée un document N-Up à partir des fichiers PDF d'entrée multiples vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont une combinaison des pages dans les fichiers d'entrée du même numéro de page. Les multiples pages sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Fichiers Pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| isSidewise | Boolean | Mode d'empilement, vrai pour horizontalement et faux pour verticalement. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Crée un document N-Up à partir des flux PDF d'entrée multiples vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont une combinaison des pages dans les flux d'entrée du même numéro de page. Les multiples pages sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStreams | Stream[] | Flux Pdf d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |
| isSidewise | Boolean | Mode d'empilement, vrai pour horizontalement et faux pour verticalement. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Crée un document N-Up à partir du fichier d'entrée vers outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Valeur de retour

true si l'opération a été complétée avec succès ; sinon, false.

## Remarques

La méthode TryMakeNUp est similaire à la méthode MakeNUp, sauf que la méthode TryMakeNUp ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Voir aussi

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)