---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Crée un livret à partir du fichier d'entrée vers le fichier de sortie
type: docs
weight: 300
url: /fr/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Crée un livret à partir du fichier d'entrée vers le fichier de sortie.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Crée un livret à partir de l'InputStream vers l'outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux pdf d'entrée. |
| outputStream | Stream | flux pdf de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Crée un livret à partir du inputFile vers le outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin et nom du fichier pdf d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| pageSize | PageSize | La taille de page du fichier pdf de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux PDF d'entrée. |
| outputStream | Stream | flux pdf de sortie. |
| pageSize | PageSize | La taille de page du fichier pdf de sortie. |

### Valeur de retour

Vrai si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Crée un livret personnalisé à partir du firstInputFile vers le outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Le fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| leftPages | Int32[] | Les pages de gauche du livret. |
| rightPages | Int32[] | Les pages de droite du livret. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Crée un livret personnalisé à partir du firstInputStream vers le outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Le flux d'entrée. |
| outputStream | Stream | flux pdf de sortie. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les pages de droite. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Crée un livret personnalisé à partir du firstInputFile vers le outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Le fichier d'entrée. |
| outputFile | String | Chemin et nom du fichier pdf de sortie. |
| pageSize | PageSize | La taille de page du fichier pdf de sortie. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les pages de droite. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Crée un livret à partir du firstInputStream vers le outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Le flux d'entrée. |
| outputStream | Stream | flux pdf de sortie. |
| pageSize | PageSize | La taille de page du fichier pdf de sortie. |
| leftPages | Int32[] | Les pages de gauche. |
| rightPages | Int32[] | Les pages de droite. |

### Valeur de retour

boolean - Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
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

Vrai si l'opération a réussi.

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Crée un livret à partir du fichier PDF et le stocke dans HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de document d'entrée. |
| pageSize | PageSize | Taille de page souhaitée. |
| leftPages | Int32[] | Tableau des numéros de page qui seront placés à gauche. |
| rightPages | Int32[] | Tableau des numéros de page qui seront placés à droite. |
| response | HttpResponse | Objet HttpResponse. |

### Valeur de retour

Vrai si l'opération a réussi.

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier source. |
| pageSize | PageSize | Taille de page souhaitée dans le fichier de sortie. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

Vrai si l'opération a réussi.

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Crée un livret à partir du fichier source et stocke le résultat dans HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de document d'entrée. |
| pageSize | PageSize | Taille de page souhaitée dans le fichier de sortie. |
| response | HttpResponse | Objet Respose où le résultat sera enregistré. |

### Valeur de retour

vrai si le livret a été construit avec succès.

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)