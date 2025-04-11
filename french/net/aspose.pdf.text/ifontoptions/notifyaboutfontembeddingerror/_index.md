---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: Propriété IFontOptions. Parfois, il n'est pas possible d'incorporer la police souhaitée dans le document. Il y a de nombreuses raisons, par exemple des restrictions de licence ou lorsque la police souhaitée n'a pas été trouvée sur l'ordinateur de destination. Lorsque cette situation se présente, il n'est pas simple de détecter, car la police souhaitée est incorporée via un ensemble de drapeaux de propriété Font.IsEmbedded = true; Bien sûr, il est possible de lire cette propriété immédiatement après qu'elle a été définie, mais ce n'est pas une approche pratique. Le drapeau NotifyAboutFontEmbeddingError impose un mécanisme d'exception pour les cas où la tentative d'incorporer la police a échoué. Si ce drapeau est défini, une exception de type [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) sera levée. Par défaut, faux.
type: docs
weight: 10
url: /fr/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## Propriété IFontOptions.NotifyAboutFontEmbeddingError

Parfois, il n'est pas possible d'incorporer la police souhaitée dans le document. Il y a de nombreuses raisons, par exemple des restrictions de licence ou lorsque la police souhaitée n'a pas été trouvée sur l'ordinateur de destination. Lorsque cette situation se présente, il n'est pas simple de détecter, car la police souhaitée est incorporée via un ensemble de drapeaux de propriété Font.IsEmbedded = true; Bien sûr, il est possible de lire cette propriété immédiatement après qu'elle a été définie, mais ce n'est pas une approche pratique. Le drapeau NotifyAboutFontEmbeddingError impose un mécanisme d'exception pour les cas où la tentative d'incorporer la police a échoué. Si ce drapeau est défini, une exception de type [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) sera levée. Par défaut, faux.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Voir aussi

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)