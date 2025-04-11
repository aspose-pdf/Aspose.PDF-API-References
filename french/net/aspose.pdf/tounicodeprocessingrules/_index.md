---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ToUnicodeProcessingRules. Cette classe décrit des règles qui peuvent être utilisées pour résoudre l'erreur Adobe Preflight "Le texte ne peut pas être mappé en Unicode"
type: docs
weight: 11110
url: /fr/net/aspose.pdf/tounicodeprocessingrules/
---
## Classe ToUnicodeProcessingRules

Cette classe décrit des règles qui peuvent être utilisées pour résoudre l'erreur Adobe Preflight "Le texte ne peut pas être mappé en Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Initialise une nouvelle instance de la classe `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Initialise une nouvelle instance de la classe `ToUnicodeProcessingRules` avec l'option spécifiée pour supprimer les espaces des noms CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Initialise une nouvelle instance de la classe `ToUnicodeProcessingRules` avec des options spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Certaines polices ne fournissent pas d'informations sur les unicodes pour certains symboles de texte. Ce manque d'information entraîne une erreur "Le texte ne peut pas être mappé en Unicode". Utilisez ce drapeau pour mapper les symboles non liés sur l'unicode "espace" (code 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Certaines polices ont des cartes de codes de caractères ToUnicode avec des espaces dans les noms. Ces espaces peuvent provoquer des erreurs lors du mappage de texte unicode. Ce drapeau ordonne de supprimer les espaces des noms des cartes de codes de caractères ToUnicode. Par défaut faux. |

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)