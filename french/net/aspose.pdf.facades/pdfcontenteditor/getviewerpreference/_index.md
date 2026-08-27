---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Retourne la préférence d'affichage"
type: docs
weight: 390
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

Renvoie la préférence d'affichage.

```csharp
public int GetViewerPreference()
```

### Valeur de retour

Renvoie l'ensemble des indicateurs ViewerPrefernece

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


