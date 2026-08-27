---
title: "FormEditor.SetFieldAppearance"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "FormEditor méthode. Définir les indicateurs du champ"
type: docs
weight: 280
url: /fr/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

Définit les indicateurs du champ

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ dont les indicateurs doivent être mis à jour. |
| flags | AnnotationFlags | Indicateur du champ. |

### Valeur de retour

true si les indicateurs ont été mis à jour avec succès.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Voir aussi

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


