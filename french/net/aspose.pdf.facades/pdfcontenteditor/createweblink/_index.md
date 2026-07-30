---
title: "PdfContentEditor.CreateWebLink"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Crée un lien web dans le document PDF"
type: docs
weight: 300
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

Crée un lien web dans le document PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle pour le clic actif. |
| url | String | La destination du lien web. |
| originalPage | Int32 | Le nombre de pages d'origine sur lesquelles le rectangle lié au lien web sera créé. |
| clr | Color | La couleur du rectangle pour le clic actif. |
| actionName | Enum[] | Le tableau d'actions (membres de l'énumération PredefinedAction) correspondant à l'exécution des éléments de menu dans le visualiseur Acrobat. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

Crée un lien web dans le document PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle pour le clic actif. |
| url | String | La destination du lien web. |
| originalPage | Int32 | Le nombre de pages d'origine où le rectangle lié au lien web sera créé. |
| clr | Color | La couleur du rectangle pour le clic actif. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

Crée un lien web dans le document PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle pour le clic actif. |
| url | String | La destination du lien web. |
| originalPage | Int32 | Le nombre de pages d'origine où le rectangle lié au lien web sera créé. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


