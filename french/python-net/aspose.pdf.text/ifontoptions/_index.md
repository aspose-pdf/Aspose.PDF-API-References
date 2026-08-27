---
title: "IFontOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Propriétés utiles pour ajuster le comportement de la Font"
type: docs
weight: 180
url: /fr/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

Propriétés utiles pour ajuster le comportement de la Font

Le type IFontOptions expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| notify_about_font_embedding_error | Il arrive parfois qu'il ne soit pas possible d'incorporer la police souhaitée dans le document. Il existe de nombreuses raisons, par exemple<br/>            des restrictions de licence ou le fait que la police souhaitée n'ait pas été trouvée sur l'ordinateur de destination.<br/>            Lorsque cette situation se produit, il n'est pas simple de la détecter, car la police souhaitée est incorporée via le réglage <br/>            du drapeau de propriété Font.IsEmbedded = true ; Bien sûr, il est possible de lire cette propriété immédiatement après qu'elle a été définie mais<br/>            ce n'est pas une approche pratique. Le drapeau NotifyAboutFontEmbeddingError impose un mécanisme d'exception <br/>            pour les cas où la tentative d'incorporation de la police a échoué. Si ce drapeau est activé, une exception du type<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) sera levée. Par défaut, false. |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

