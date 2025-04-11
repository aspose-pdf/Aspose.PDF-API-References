---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Divise le fichier Pdf à partir de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant en tant que nouveau fichier
type: docs
weight: 340
url: /fr/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Divise le fichier Pdf à partir de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant en tant que nouveau fichier.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf source. |
| location | Int32 | Le point de division. |
| outputFile | String | Fichier Pdf de sortie. |

### Valeur de retour

Vrai pour le succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Divise depuis le début jusqu'à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de fichier Pdf source. |
| location | Int32 | Le point de division. |
| outputStream | Stream | Flux de fichier de sortie. |

### Valeur de retour

Vrai pour le succès, ou faux.

## Remarques

Les flux NE sont PAS fermés après cette opération.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)