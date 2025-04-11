---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Signatures.SignaturesCoverage. Représente l'énumération pour le niveau de couverture fourni par les signatures numériques dans un document
type: docs
weight: 10110
url: /fr/net/aspose.pdf.signatures/signaturescoverage/
---
## Énumération SignaturesCoverage

Représente l'énumération pour le niveau de couverture fourni par les signatures numériques dans un document.

```csharp
public enum SignaturesCoverage
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Undefined | `0` | Indique que l'état de la couverture des signatures numériques dans le document est indéfini. Cette valeur est généralement utilisée lorsque une ou plusieurs signatures dans le document sont compromises ou ne peuvent pas être vérifiées, empêchant une évaluation définitive de la couverture des signatures du document. |
| EntirelySigned | `1` | Indique que le document est entièrement couvert par des signatures numériques. Cette valeur signifie que toutes les parties requises du document ont été signées et qu'aucune signature n'est compromise. |
| PartiallySigned | `2` | Indique que le document est partiellement signé, ce qui signifie que certaines, mais pas toutes, de ses parties sont couvertes par des signatures numériques. Cette valeur est utilisée lorsque certaines parties du document restent non signées ou sont exclues de la couverture des signatures. |

### Voir aussi

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)