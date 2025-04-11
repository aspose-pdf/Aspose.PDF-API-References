---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Change la préférence d'affichage
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## Méthode PdfContentEditor.ChangeViewerPreference

Change la préférence d'affichage.

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

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)