---
title: TrySplitFromFirst
second_title: Référence de l'API Aspose.PDF pour .NET
description: Divise le fichier PDF de la première page à lemplacement spécifié et enregistre la partie avant en tant que nouveau fichier.
type: docs
weight: 490
url: /fr/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_2}

Divise le fichier PDF de la première page à l'emplacement spécifié et enregistre la partie avant en tant que nouveau fichier.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Fichier PDF source. |
| location | Int32 | Le point de partage. |
| outputFile | String | Fichier PDF de sortie. |

### Return_Value

Vrai pour le succès, ou faux.

### Remarques

La méthode TrySplitFromFirst est similaire à la méthode SplitFromFirst , sauf que la méthode TrySplitFromFirst ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Fractionne du début à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de fichiers source Pdf. |
| location | Int32 | Le point de partage. |
| outputStream | Stream | Fichier de sortie Flux. |

### Return_Value

Vrai pour le succès, ou faux.

### Remarques

Les flux ne sont PAS fermés après cette opération. La méthode TrySplitFromFirst est similaire à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Divise le document de la première page à l'emplacement et enregistre le résultat dans des objets HttpResponse.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputFile | String | Nom du fichier source. |
| location | Int32 | Point de partage. |
| response | HttpResponse | Objets HTTPResponse. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TrySplitFromFirst est similaire à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Divise le document du début à l'emplacement spécifié et stocke le résultat dans l'objet HttpResponse.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux de document source. |
| location | Int32 | Le point de partage. |
| response | HttpResponse | Objet HttpResponse où le résultat sera stocké. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TrySplitFromFirst est similaire à la méthode SplitFromFirst, sauf que la méthode TrySplitFromFirst ne lève pas d'exception si l'opération échoue.

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->