---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Divise le fichier PDF en documents d'une seule page
type: docs
weight: 370
url: /fr/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Divise le fichier PDF en documents d'une seule page.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Nom du fichier PDF d'entrée. |

### Valeur de retour

Flux PDF de sortie, chaque flux tamponne un document PDF d'une seule page.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Divise le fichier Pdf en documents d'une seule page.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux Pdf d'entrée. |

### Valeur de retour

Tableau de flux mémoire contenant les pages du document.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Divise le fichier Pdf en documents d'une seule page et les enregistre dans le chemin spécifié. Le chemin est spécifié par le nom de champ modèle.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Nom du fichier d'entrée. |
| fileNameTemplate | String | Modèle du nom de fichier résultant. Doit contenir %NUM% qui est remplacé par le numéro de page. Par exemple, si c:/dir/page%NUM%.pdf est spécifié, les fichiers résultants auront les noms suivants : c:/dir/page1.pdf, c:/dir/page2.pdf, etc. |

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Divise le fichier Pdf en documents d'une seule page et les enregistre dans le chemin spécifié. Le chemin est spécifié par le nom de champ modèle.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux du document source. |
| fileNameTemplate | String | Modèle du nom de fichier résultant. Doit contenir %NUM% qui est remplacé par le numéro de page. Par exemple, si c:/dir/page%NUM%.pdf est spécifié, les fichiers résultants auront les noms suivants : c:/dir/page1.pdf, c:/dir/page2.pdf, etc. |

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)