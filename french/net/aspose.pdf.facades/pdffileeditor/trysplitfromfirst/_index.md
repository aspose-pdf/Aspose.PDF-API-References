---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Divise le fichier Pdf depuis la première page jusqu'à l'emplacement spécifié et enregistre la partie avant en tant que nouveau fichier
type: docs
weight: 460
url: /fr/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Divise le fichier Pdf depuis la première page jusqu'à l'emplacement spécifié et enregistre la partie avant en tant que nouveau fichier.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier Pdf source. |
| location | Int32 | Le point de division. |
| outputFile | String | Fichier Pdf de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

La méthode TrySplitFromFirst est semblable à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Divise depuis le début jusqu'à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du fichier Pdf source. |
| location | Int32 | Le point de division. |
| outputStream | Stream | Flux de fichier de sortie. |

### Valeur de retour

Vrai en cas de succès, ou faux.

## Remarques

Les flux NE sont PAS fermés après cette opération. La méthode TrySplitFromFirst est semblable à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Divise le document depuis la première page jusqu'à l'emplacement et enregistre le résultat dans des objets HttpResponse.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Nom du fichier source. |
| location | Int32 | Point de division. |
| response | HttpResponse | Objets HttpResponse. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TrySplitFromFirst est semblable à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Divise le document depuis le début jusqu'à l'emplacement spécifié et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du document source. |
| location | Int32 | Le point de division. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Valeur de retour

vrai si l'opération s'est terminée avec succès ; sinon, faux.

## Remarques

La méthode TrySplitFromFirst est semblable à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lance pas d'exception si l'opération échoue.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)