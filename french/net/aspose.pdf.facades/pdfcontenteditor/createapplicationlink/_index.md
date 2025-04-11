---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée un lien pour lancer une application dans un document PDF
type: docs
weight: 110
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Crée un lien pour lancer une application dans un document PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle pour le clic actif. |
| application | String | Le chemin de l'application à lancer. |
| page | Int32 | Le numéro de la page originale où le rectangle lié au lien sera créé. |
| clr | Color | La couleur du rectangle pour le clic actif. |
| actionName | Enum[] | Le tableau d'actions (membres de l'énumération PredefinedAction) correspondant à l'exécution des éléments de menu dans le visualiseur Acrobat. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Crée un lien pour lancer une application dans un document PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle pour le clic actif. |
| application | String | Le chemin de l'application à lancer. |
| page | Int32 | Le numéro de la page originale où le rectangle lié au lien sera créé. |
| clr | Color | La couleur du rectangle pour le clic actif. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Crée un lien pour lancer une application dans un document PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle pour le clic actif. |
| application | String | Le chemin de l'application à lancer. |
| page | Int32 | Le numéro de la page originale où le rectangle lié au lien sera créé. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)