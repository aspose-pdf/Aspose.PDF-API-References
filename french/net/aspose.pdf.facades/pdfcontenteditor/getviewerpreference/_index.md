---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Renvoie la préférence de vue
type: docs
weight: 390
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## Méthode PdfContentEditor.GetViewerPreference

Renvoie la préférence de vue.

```csharp
public int GetViewerPreference()
```

### Valeur de retour

Renvoie un ensemble de drapeaux ViewerPrefernece

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)