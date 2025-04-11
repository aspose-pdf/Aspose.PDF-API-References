---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. Certains documents PDF contiennent des symboles unicode spéciaux qui appartiennent à la Zone d'Utilisation Privée (PUA), voir la description sur https//en.wikipedia.org/wiki/Private_Use_Areas. Ces symboles provoquent des erreurs de conformité PDF/A telles que "Le texte est mappé à la Zone d'Utilisation Privée Unicode mais aucune entrée ActualText n'est présente". Cette énumération déclare des stratégies qui peuvent être utilisées pour gérer les symboles PUA.
type: docs
weight: 8390
url: /fr/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## Énumération PdfFormatConversionOptions.PuaProcessingStrategy

Certains documents PDF contiennent des symboles unicode spéciaux, qui appartiennent à la Zone d'Utilisation Privée (PUA), voir la description à https://en.wikipedia.org/wiki/Private_Use_Areas. Ces symboles provoquent des erreurs de conformité PDF/A telles que "Le texte est mappé à la Zone d'Utilisation Privée Unicode mais aucune entrée ActualText n'est présente". Cette énumération déclare des stratégies qui peuvent être utilisées pour gérer les symboles PUA.

```csharp
public enum PuaProcessingStrategy
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Aucun | `0` | Désactiver le traitement des symboles PUA. Cette stratégie est utilisée par défaut pour les documents PDF/A avec conformité de niveau B. |
| EntourerTextePuaAvecTexteActualVide | `1` | Insère un bloc de contenu marqué avec une entrée ActualText qui contient du texte vide. Cette stratégie donne de bons résultats pour les documents sans blocs de contenu marqués. Utilisée par défaut pour les documents PDF/A avec conformité de niveau A. |
| SubstituerSymbolesPua | `2` | Cette stratégie fonctionne plus lentement que 'EntourerTextePuaAvecTexteActualVide' mais elle peut supprimer les erreurs de conformité PUA pour les documents qui ne peuvent pas être traités correctement par EntourerTextePuaAvecTexteActualVide. Les symboles PUA sont substitués par le symbole 'espace' ou un unicode spécial (certains symboles PUA ont des analogues unicode). La substitution s'applique non pas au texte du document mais aux données internes de la police ToUnicode, donc cela n'affecte pas la vision du symbole mais cela affecte la présentation du symbole dans le système de tampon d'opération de copier/coller. |

### Voir aussi

* classe [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)