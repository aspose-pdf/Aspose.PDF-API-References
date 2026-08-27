---
title: "Interface IFontOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Interface Aspose.Pdf.Text.IFontOptions. Propriétés utiles pour ajuster le comportement des polices"
type: docs
weight: 10790
url: /fr/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

Propriétés utiles pour ajuster le comportement de la police

```csharp
public interface IFontOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Parfois, il n'est pas possible d'incorporer la police souhaitée dans le document. Il existe de nombreuses raisons, par exemple des restrictions de licence ou le fait que la police souhaitée n'ait pas été trouvée sur l'ordinateur de destination. Lorsque cette situation se produit, il n'est pas simple de la détecter, car la police souhaitée est incorporée via le drapeau de propriété `Font.IsEmbedded = true;`. Bien sûr, il est possible de lire cette propriété immédiatement après qu'elle a été définie, mais ce n'est pas une approche pratique. Le drapeau `NotifyAboutFontEmbeddingError` impose un mécanisme d'exception pour les cas où la tentative d'incorporation de la police échoue. Si ce drapeau est activé, une exception du type [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) sera levée. Par défaut, false. |

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


