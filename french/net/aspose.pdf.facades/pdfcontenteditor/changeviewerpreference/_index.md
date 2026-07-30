---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Modifie la préférence d'affichage"
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

Modifie la préférence d'affichage.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| viewerAttribution | Int32 | L'attribution d'affichage définie dans la classe ViewerPreference. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


