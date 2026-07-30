---
title: "PdfFileEditor.SplitFromFirst"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Divise le fichier Pdf à partir de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant comme un nouveau fichier."
type: docs
weight: 340
url: /fr/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié, et enregistre la partie avant comme un nouveau fichier.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf source. |
| emplacement | Int32 | Le point de division. |
| outputFile | String | Fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Divise du début jusqu'à l'emplacement spécifié, et enregistre la partie avant dans le flux de sortie Stream.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier Pdf source. |
| emplacement | Int32 | Le point de division. |
| outputStream | Stream | Flux du fichier de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

Les flux ne sont PAS fermés après cette opération.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


