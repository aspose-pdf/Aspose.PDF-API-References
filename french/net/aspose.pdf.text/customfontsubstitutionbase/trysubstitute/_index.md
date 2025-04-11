---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: Méthode CustomFontSubstitutionBase. Remplace la police originale par une autre police
type: docs
weight: 20
url: /fr/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## Méthode CustomFontSubstitutionBase.TrySubstitute

Remplace la police originale par une autre police.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Spécification de la police originale. |
| substitutionFont | Font& | Police de substitution. |

### Valeur de retour

Vrai en cas de succès de la substitution.

## Remarques

La classe CustomFontSubstitutionBase doit être héritée pour implémenter la logique de substitution de police personnalisée. La méthode TrySubstitute doit être correctement remplacée : doit retourner vrai en cas de substitution requise. substitutionFont doit être défini sur un objet Font valide. Doit retourner faux en cas de non-requête de substitution. substitutionFont peut être défini sur null.

### Voir aussi

* classe [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* classe [Font](../../font/)
* classe [CustomFontSubstitutionBase](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)