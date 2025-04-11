---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Divise à partir de l'emplacement et enregistre la partie arrière en tant que nouveau fichier
type: docs
weight: 470
url: /fr/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Divise à partir de l'emplacement et enregistre la partie arrière en tant que nouveau fichier.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf source. |
| location | Int32 | La position de division. |
| outputFile | String | Chemin du fichier Pdf de sortie. |

### Valeur de retour

Vrai pour le succès, ou faux.

## Remarques

La méthode TrySplitToEnd est comme la méthode SplitToEnd, sauf que la méthode TrySplitToEnd ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Divise à partir de l'emplacement spécifié et enregistre la partie arrière en tant que nouveau fichier Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de fichier Pdf source. |
| location | Int32 | La position de division. |
| outputStream | Stream | Flux de fichier Pdf de sortie. |

### Valeur de retour

Vrai pour le succès, ou faux.

## Remarques

Les flux NE sont PAS fermés après cette opération, sauf si CloseConcatedStreams est spécifié. La méthode TrySplitToEnd est comme la méthode SplitToEnd, sauf que la méthode TrySplitToEnd ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpResponse.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux de document source. |
| location | Int32 | Point de division. |
| response | HttpResponse | Objet HttpResponse. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TrySplitToEnd est comme la méthode SplitToEnd, sauf que la méthode TrySplitToEnd ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpResponse.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | nom du fichier source. |
| location | Int32 | Point de division. |
| response | HttpResponse | Objets HttpResponse. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TrySplitToEnd est comme la méthode SplitToEnd, sauf que la méthode TrySplitToEnd ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)