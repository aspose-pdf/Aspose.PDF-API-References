---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: Méthode SignaturesCompromiseDetector. Vérifiez les signatures numériques du document pour détection de compromission
type: docs
weight: 20
url: /fr/net/aspose.pdf/signaturescompromisedetector/check/
---
## Méthode SignaturesCompromiseDetector.Check

Vérifiez les signatures numériques du document pour détection de compromission.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | Le résultat de la vérification du document. |

### Valeur de retour

Vrai, si la compromission des signatures n'est pas détectée.

## Remarques

L'utilisation de cette méthode pour un document dans lequel il n'y a pas de signatures numériques renverra `True`.

### Voir aussi

* classe [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* classe [SignaturesCompromiseDetector](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)