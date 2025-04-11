---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Crée un livret à partir du fichier d'entrée vers le fichier de sortie
type: docs
weight: 430
url: /fr/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageSize | PageSize | Taille de page souhaitée. |
| leftPages | Int32[] | Tableau des numéros de page à placer à gauche. |
| rightPages | Int32[] | Tableau des numéros de page à placer à droite. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Crée un livret à partir d'un fichier PDF et le stocke dans HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de document d'entrée. |
| pageSize | PageSize | Taille de page souhaitée. |
| leftPages | Int32[] | Tableau des numéros de page qui seront placés à gauche. |
| rightPages | Int32[] | Tableau des numéros de page qui seront placés à droite. |
| response | HttpResponse | Objet HttpResponse. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageSize | PageSize | Taille de page souhaitée dans le fichier de sortie. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

True si l'opération a réussi.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Crée un livret à partir du fichier source et stocke le résultat dans HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de document d'entrée. |
| pageSize | PageSize | Taille de page souhaitée dans le fichier de sortie. |
| response | HttpResponse | Objet de réponse où le résultat sera enregistré. |

### Valeur de retour

true si le livret a été construit avec succès.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Crée un livret à partir du fichier d'entrée vers le fichier de sortie.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier PDF d'entrée. |
| outputFile | String | Chemin et nom du fichier PDF de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Crée un livret à partir de InputStream vers outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux PDF d'entrée. |
| outputStream | Stream | Flux PDF de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Crée un livret à partir de inputFile vers outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier PDF d'entrée. |
| outputFile | String | Chemin et nom du fichier PDF de sortie. |
| pageSize | PageSize | La taille de page du fichier PDF de sortie. |

### Valeur de retour

True si l'opération a réussi.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux PDF d'entrée. |
| outputStream | Stream | Flux PDF de sortie. |
| pageSize | PageSize | La taille de page du fichier PDF de sortie. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Crée un livret personnalisé à partir de firstInputFile vers outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Le fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier PDF de sortie. |
| leftPages | Int32[] | Les pages de gauche du livret. |
| rightPages | Int32[] | Les pages de droite du livret. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Crée un livret personnalisé à partir de firstInputStream vers outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Le flux d'entrée. |
| outputStream | Stream | Flux PDF de sortie. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les pages de droite. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Crée un livret personnalisé à partir de firstInputFile vers outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Le fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier PDF de sortie. |
| pageSize | PageSize | La taille de page du fichier PDF de sortie. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les pages de droite. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Crée un livret à partir de firstInputStream vers outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Le flux d'entrée. |
| outputStream | Stream | Flux PDF de sortie. |
| pageSize | PageSize | La taille de page du fichier PDF de sortie. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les pages de droite. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryMakeBooklet est similaire à la méthode MakeBooklet, sauf que la méthode TryMakeBooklet ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)