---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: Propriété OriginalFontSpecification. Obtient une valeur qui indique que la substitution est inévitable
type: docs
weight: 20
url: /fr/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## Propriété CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable

Obtient une valeur qui indique que la substitution est inévitable.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Remarques

Renvoie vrai si une substitution a été demandée en raison de l'absence de la police originale ou si la police originale ne peut pas être utilisée dans le contexte d'une tâche. Si l'utilisateur ignore le drapeau et ne substitue pas la police, la procédure de substitution de police par défaut est effectuée. Mais cela offre à l'utilisateur la possibilité de remplacer la procédure de substitution de police standard et de définir une meilleure police pour le système. Renvoie faux si la police originale est présente, valide, mais il est permis à l'utilisateur de la substituer.

### Voir aussi

* classe [OriginalFontSpecification](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)