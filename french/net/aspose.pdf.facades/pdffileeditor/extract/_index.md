---
title: "PdfFileEditor.Extract"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Extrait les pages du fichier d'entrée et les enregistre comme un nouveau fichier Pdf."
type: docs
weight: 280
url: /fr/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Extrait les pages du fichier d'entrée, puis enregistre un nouveau fichier Pdf.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Chemin du fichier Pdf d'entrée. |
| startPage | Int32 | Numéro de page de début. |
| endPage | Int32 | Numéro de page de fin. |
| outputFile | String | Chemin du fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Extrait les pages spécifiées par un tableau de numéros, puis enregistre un nouveau fichier PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
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
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extrait les pages du fichier d'entrée, puis enregistre un nouveau fichier Pdf.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier d'entrée. |
| startPage | Int32 | Numéro de page de début. |
| endPage | Int32 | Numéro de page de fin. |
| outputStream | Stream | Flux de fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extrait les pages spécifiées par un tableau de numéros, puis enregistre un nouveau fichier Pdf.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
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
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


