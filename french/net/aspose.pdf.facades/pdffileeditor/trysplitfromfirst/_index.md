---
title: "PdfFileEditor.TrySplitFromFirst"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Divise le fichier Pdf à partir de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant comme un nouveau fichier."
type: docs
weight: 460
url: /fr/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié, et enregistre la partie avant comme un nouveau fichier.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf source. |
| emplacement | Int32 | Le point de division. |
| outputFile | String | Fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TrySplitFromFirst est similaire à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Divise du début jusqu'à l'emplacement spécifié, et enregistre la partie avant dans le flux de sortie Stream.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier Pdf source. |
| emplacement | Int32 | Le point de division. |
| outputStream | Stream | Flux du fichier de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

Les flux ne sont PAS fermés après cette opération. La méthode TrySplitFromFirst est similaire à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


