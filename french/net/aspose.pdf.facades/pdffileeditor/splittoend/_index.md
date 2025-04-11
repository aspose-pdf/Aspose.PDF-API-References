---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Divise à partir de l'emplacement et enregistre la partie arrière en tant que nouveau fichier
type: docs
weight: 360
url: /fr/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Divise à partir de l'emplacement spécifié et enregistre la partie arrière en tant que nouveau fichier Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de fichier Pdf source. |
| location | Int32 | La position de division. |
| outputStream | Stream | Flux de fichier Pdf de sortie. |

### Valeur de retour

Vrai pour le succès, ou faux.

## Remarques

Les flux NE sont PAS fermés après cette opération, sauf si CloseConcatedStreams est spécifié.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Divise à partir de l'emplacement et enregistre la partie arrière en tant que nouveau fichier.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf source. |
| location | Int32 | La position de division. |
| outputFile | String | Chemin du fichier Pdf de sortie. |

### Valeur de retour

Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Divise à partir de l'emplacement spécifié et enregistre la partie arrière en tant que nouveau fichier Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de fichier Pdf source. |
| location | Int32 | La position de division. |
| outputStream | Stream | Flux de fichier Pdf de sortie. |

### Valeur de retour

Vrai pour le succès, ou faux.

## Remarques

Les flux NE sont PAS fermés après cette opération, sauf si CloseConcatedStreams est spécifié.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)