---
title: "SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une énumération du niveau de couverture fourni par les signatures numériques dans un document."
type: docs
weight: 40
url: /fr/java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

Représente une énumération du niveau de couverture fourni par les signatures numériques dans un document.

## Champs

| Champ | Description |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | Indique que le document est entièrement couvert par des signatures numériques. Cette valeur signifie que toutes les parties requises du document ont été signées et qu'aucune signature n'est compromise. |
| [PartiallySigned](#PartiallySigned) | Indique que le document est partiellement signé, ce qui signifie que certaines, mais pas toutes, ses parties sont couvertes par des signatures numériques. Cette valeur est utilisée lorsque certaines parties du document restent non signées ou sont exclues de la couverture des signatures. |
| [Undefined](#Undefined) | Indique que l'état de la couverture des signatures numériques dans le document est indéfini. Cette valeur est généralement utilisée lorsqu'une ou plusieurs signatures du document sont compromises ou ne peuvent pas être vérifiées, empêchant une évaluation définitive de la couverture des signatures du document. |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

Indique que le document est entièrement couvert par des signatures numériques. Cette valeur signifie que toutes les parties requises du document ont été signées et qu'aucune signature n'est compromise.

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

Indique que le document est partiellement signé, ce qui signifie que certaines, mais pas toutes, ses parties sont couvertes par des signatures numériques. Cette valeur est utilisée lorsque certaines parties du document restent non signées ou sont exclues de la couverture des signatures.

### Undefined {#Undefined}
```
public static final int Undefined
```

Indique que l'état de la couverture des signatures numériques dans le document est indéfini. Cette valeur est généralement utilisée lorsqu'une ou plusieurs signatures du document sont compromises ou ne peuvent pas être vérifiées, empêchant une évaluation définitive de la couverture des signatures du document.
