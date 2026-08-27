---
title: "CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété OriginalFontSpecification. Obtient une valeur qui indique que la substitution est inévitable."
type: docs
weight: 20
url: /fr/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable property

Obtient une valeur indiquant que la substitution est inévitable.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Remarques

Renvoie true si la substitution a été demandée en raison de l'absence de la police d'origine ou si la police d'origine ne peut pas être utilisée dans le contexte d'une tâche. Si l'utilisateur ignore le drapeau et ne substitue pas la police, la procédure de substitution de police par défaut est exécutée. Mais cela offre à l'utilisateur la possibilité de remplacer la procédure de substitution de police standard et de définir une meilleure police pour le système. Renvoie false si la police d'origine est présente, valide, mais que l'utilisateur est autorisé à la substituer.

### Voir aussi

* class [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


