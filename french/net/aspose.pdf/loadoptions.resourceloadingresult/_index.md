---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LoadOptionsResourceLoadingResult. Résultat du chargement personnalisé de la ressource
type: docs
weight: 6150
url: /fr/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## Classe LoadOptions.ResourceLoadingResult

Résultat du chargement personnalisé de la ressource

```csharp
public class ResourceLoadingResult
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Crée une instance du résultat de chargement |

## Propriétés

| Nom | Description |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Données binaires chargées avec le chargeur personnalisé - elles doivent être définies après le chargement |

## Champs

| Nom | Description |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Parfois, l'encodage de la ressource est connu après ou pendant le chargement. Dans ce cas, le code personnalisé peut fournir un convertisseur avec cette connaissance via ce paramètre. Vous pouvez laisser null dans ce paramètre si l'encodage est inconnu ou n'a pas d'importance. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Parfois, il est impossible de charger la ressource demandée pour une raison quelconque. L'indisponibilité de la ressource ne conduit souvent pas à un plantage de la conversion et le document résultant peut être créé de toute façon (mais peut-être avec une qualité un peu inférieure, sans images, etc.). Si une exception s'est produite pendant le chargement, il suffit de la capturer et de la mettre dans ce paramètre - parfois cette information est utile pour le convertisseur pour le rendu du résultat. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Parfois, pour certaines raisons, le chargement ne doit pas se produire dans le code personnalisé. Dans ce cas, veuillez définir ce drapeau sur True. Dans ce cas, le convertisseur essaiera d'utiliser le chargeur de ressources par défaut interne pour obtenir ce résultat (comme il se comporte dans une situation où la stratégie personnalisée n'est pas fournie). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Parfois, la connaissance du type MIME de la ressource chargée est utile pour le convertisseur. Vous pouvez fournir le type MIME (s'il est connu après le chargement) dans ce paramètre. Veuillez laisser le paramètre égal à null lorsque le type MIME est inconnu ou qu'il n'est pas nécessaire de le fournir. |

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)