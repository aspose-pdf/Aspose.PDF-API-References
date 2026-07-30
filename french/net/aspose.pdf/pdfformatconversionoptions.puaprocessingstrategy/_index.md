---
title: "Enum PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Enum Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. Certains documents PDF contiennent des symboles Unicode spéciaux appartenant à la zone d'utilisation privée (PUA), voir la description à https//en.wikipedia.org/wiki/Private_Use_Areas. Ces symboles provoquent des erreurs de conformité PDF/A telles que \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\". Cette énumération déclare des stratégies pouvant être utilisées pour gérer les symboles PUA."
type: docs
weight: 8530
url: /fr/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

Certains documents PDF contiennent des symboles Unicode spéciaux appartenant à la zone d'utilisation privée (PUA), voir la description à https://en.wikipedia.org/wiki/Private_Use_Areas. Ces symboles provoquent des erreurs de conformité PDF/A comme "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Cette énumération déclare des stratégies pouvant être utilisées pour gérer les symboles PUA.

```csharp
public enum PuaProcessingStrategy
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Désactiver le traitement des symboles PUA. Cette stratégie est utilisée par défaut pour les documents PDF/A avec conformité de niveau B. |
| SurroundPuaTextWithEmptyActualText | `1` | Insère un bloc de contenu marqué avec une entrée ActualText contenant du texte vide. Cette stratégie donne de bons résultats pour les documents sans blocs de contenu marqués. Utilisée par défaut pour les documents PDF/A avec conformité de niveau A. |
| SubstitutePuaSymbols | `2` | Cette stratégie fonctionne plus lentement que 'SurroundPuaTextWithEmptyActualText' mais elle peut éliminer les erreurs de conformité PUA pour les documents qui ne peuvent pas être correctement traités par SurroundPuaTextWithEmptyActualText. Les symboles PUA sont remplacés par le symbole 'espace' ou par un Unicode spécial (certains symboles PUA ont des analogues Unicode). La substitution s'applique non pas au texte du document mais aux données internes de la police ToUnicode, ce qui n'affecte pas la visibilité du symbole mais affecte sa présentation lors des opérations de copier‑coller dans le presse‑papier du système. |

### Voir aussi

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


