---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode CustomFontSubstitutionBase. Remplace la police originale par une autre police"
type: docs
weight: 20
url: /fr/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

Remplace la police d'origine par une autre police.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Spécification de la police originale. |
| substitutionFont | Font& | Police de substitution. |

### Valeur de retour

Vrai si la substitution a réussi.

## Remarques

La classe CustomFontSubstitutionBase doit être héritée pour implémenter une logique de substitution de police personnalisée. La méthode TrySubstitute doit être correctement remplacée : elle doit renvoyer true si une substitution est requise. substitutionFont doit être défini sur un objet Font valide. Elle doit renvoyer false si aucune substitution n’est requise. substitutionFont peut être défini sur null.

### Voir aussi

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


