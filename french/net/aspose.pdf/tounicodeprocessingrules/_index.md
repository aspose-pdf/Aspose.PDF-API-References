---
title: "Classe ToUnicodeProcessingRules"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.ToUnicodeProcessingRules. Cette classe décrit les règles pouvant être utilisées pour résoudre l'erreur Adobe Preflight \"Text cannot be mapped to Unicode\""
type: docs
weight: 11300
url: /fr/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

Cette classe décrit les règles qui peuvent être utilisées pour résoudre l'erreur Adobe Preflight « Le texte ne peut pas être mappé à Unicode ».

```csharp
public class ToUnicodeProcessingRules
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Initialise une nouvelle instance de la classe `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Initialise une nouvelle instance de la classe `ToUnicodeProcessingRules` avec l'option spécifiée pour supprimer les espaces des noms CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Initialise une nouvelle instance de la classe `ToUnicodeProcessingRules` avec les options spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Certaines polices ne fournissent pas d'informations sur les unicodes pour certains symboles de texte. Cette absence d'information déclenche une erreur "Text cannot be mapped to Unicode". Utilisez ce drapeau pour mapper les symboles non liés sur le caractère unicode "espace" (code 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Certaines polices ont des cartes de codes de caractères ToUnicode avec des espaces dans les noms. Ces espaces peuvent provoquer des erreurs lors du mappage du texte unicode. Ce drapeau indique de supprimer les espaces des noms des cartes de codes de caractères ToUnicode. Par défaut, false. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


