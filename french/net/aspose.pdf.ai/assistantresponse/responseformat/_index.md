---
title: AssistantResponse.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: Propriété AssistantResponse. Obtient ou définit le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Définir sur "type""json_object" active le mode JSON, ce qui garantit que le message généré par le modèle est un JSON valide. Important  lors de l'utilisation du mode JSON, vous devez également instruire le modèle à produire du JSON vous-même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux interminable d'espaces blancs jusqu'à ce que la génération atteigne la limite de jetons, ce qui entraîne une demande de longue durée et apparemment "bloquée". Notez également que le contenu du message peut être partiellement coupé si finish_reason="length", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte.
type: docs
weight: 100
url: /fr/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## Propriété AssistantResponse.ResponseFormat

Obtient ou définit le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Définir sur { "type": "json_object" } active le mode JSON, ce qui garantit que le message généré par le modèle est un JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également instruire le modèle à produire du JSON vous-même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux interminable d'espaces blancs jusqu'à ce que la génération atteigne la limite de jetons, ce qui entraîne une demande de longue durée et apparemment "bloquée". Notez également que le contenu du message peut être partiellement coupé si finish_reason="length", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Voir aussi

* classe [ResponseFormat](../../responseformat/)
* classe [AssistantResponse](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)