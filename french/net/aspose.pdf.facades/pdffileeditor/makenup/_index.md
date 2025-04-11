---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Crée un document NUp à partir des deux flux PDF d'entrée vers outputStream
type: docs
weight: 310
url: /fr/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Crée un document N-Up à partir du firstInputFile vers outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux pdf d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux pdf d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page provenant du premier fichier d'entrée et une autre du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputFile | String | premier fichier d'entrée. |
| secondInputFile | String | deuxième fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Crée un document N-Up à partir des deux flux PDF d'entrée vers outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | premier flux d'entrée. |
| secondInputStream | Stream | deuxième flux d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Crée un document N-Up à partir des fichiers PDF d'entrée multiples vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont une combinaison des pages dans les fichiers d'entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | Fichiers Pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| isSidewise | Boolean | Mode d'empilement, vrai pour horizontalement et faux pour verticalement. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Crée un document N-Up à partir des flux PDF d'entrée multiples vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont une combinaison des pages dans les flux d'entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStreams | Stream[] | Flux Pdf d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |
| isSidewise | Boolean | Mode d'empilement, vrai pour horizontalement et faux pour verticalement. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Crée un document N-Up à partir du fichier d'entrée vers outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Crée un document N-Up à partir du firstInputFile vers outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux pdf d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux pdf d'entrée. |
| outputStream | Stream | Flux pdf de sortie. |
| x | Int32 | Nombre de colonnes. |
| y | Int32 | Nombre de lignes. |
| pageSize | PageSize | La taille de la page du fichier pdf de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page provenant du premier fichier d'entrée et une autre du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| firstInputFile | String | premier fichier d'entrée. |
| secondInputFile | String | deuxième fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)