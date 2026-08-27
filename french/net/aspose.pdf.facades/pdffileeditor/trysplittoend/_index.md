---
title: "PdfFileEditor.TrySplitToEnd"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Divise à partir de l'emplacement et enregistre la partie arrière comme un nouveau fichier."
type: docs
weight: 470
url: /fr/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Divise à partir de l'emplacement, et enregistre la partie arrière comme un nouveau fichier.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf source. |
| emplacement | Int32 | La position de division. |
| outputFile | String | Chemin du fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TrySplitToEnd est similaire à la méthode SplitToEnd, sauf que la méthode TrySplitToEnd ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Divise à partir de l'emplacement spécifié, et enregistre la partie arrière comme un nouveau flux de fichier Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier Pdf source. |
| emplacement | Int32 | La position de division. |
| outputStream | Stream | Flux de fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

Les flux NE sont PAS fermés après cette opération sauf si CloseConcatedStreams est spécifié. La méthode TrySplitToEnd est similaire à la méthode SplitToEnd, sauf que la méthode TrySplitToEnd ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


