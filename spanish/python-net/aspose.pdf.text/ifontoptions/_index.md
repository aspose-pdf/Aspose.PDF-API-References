---
title: "IFontOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Propiedades útiles para ajustar el comportamiento de Font"
type: docs
weight: 180
url: /es/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

Propiedades útiles para ajustar el comportamiento de Font

El tipo IFontOptions expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| notify_about_font_embedding_error | A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo<br/>            restricciones de licencia o cuando la fuente deseada no se encuentra en el equipo de destino.<br/>            Cuando ocurre esta situación no es sencillo detectarla, porque la fuente deseada se incrusta mediante el establecimiento <br/>            de la bandera de propiedad Font.IsEmbedded = true; Por supuesto es posible leer esta propiedad inmediatamente después de establecerla pero<br/>            no es un enfoque conveniente. La bandera NotifyAboutFontEmbeddingError aplica un mecanismo de excepción <br/>            para los casos en que el intento de incrustar la fuente falla. Si esta bandera está activada se lanzará una excepción del tipo<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) . Por defecto false. |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

