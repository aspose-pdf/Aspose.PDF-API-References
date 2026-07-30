---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété IFontOptions. Parfois il n'est pas possible d'intégrer la police souhaitée dans le document. Il existe de nombreuses raisons, par exemple des restrictions de licence ou le fait que la police souhaitée n'ait pas été trouvée sur l'ordinateur de destination. Dans cette situation, il n'est pas simple de la détecter car la police souhaitée est intégrée via le drapeau de propriété Font.IsEmbedded true. Bien sûr, il est possible de lire cette propriété immédiatement après qu'elle a été définie, mais ce n'est pas une approche pratique. Le drapeau NotifyAboutFontEmbeddingError impose un mécanisme d'exception pour les cas où la tentative d'intégration de la police échoue. Si ce drapeau est activé, une exception de type FontEmbeddingException sera levée. Par défaut false."
type: docs
weight: 10
url: /fr/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

Parfois il n'est pas possible d'intégrer la police souhaitée dans le document. Il existe de nombreuses raisons, par exemple des restrictions de licence ou le fait que la police souhaitée n'ait pas été trouvée sur l'ordinateur de destination. Dans cette situation, il n'est pas simple de la détecter, car la police souhaitée est intégrée via le drapeau de propriété Font.IsEmbedded = true ; Bien sûr, il est possible de lire cette propriété immédiatement après qu'elle a été définie, mais ce n'est pas une approche pratique. Le drapeau NotifyAboutFontEmbeddingError impose un mécanisme d'exception pour les cas où la tentative d'intégration de la police échoue. Si ce drapeau est activé, une exception de type [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) sera levée. Par défaut false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Voir aussi

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


