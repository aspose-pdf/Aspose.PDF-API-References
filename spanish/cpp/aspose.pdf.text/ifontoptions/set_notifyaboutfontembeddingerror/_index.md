---
title: "Método set_NotifyAboutFontEmbeddingError de Aspose::Pdf::Text::IFontOptions"
linktitle: "set_NotifyAboutFontEmbeddingError"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método set_NotifyAboutFontEmbeddingError de Aspose::Pdf::Text::IFontOptions. A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo restricciones de licencia o cuando la fuente deseada no se encuentra en el equipo de destino. Cuando ocurre esta situación no es sencillo detectarla, porque la fuente deseada se incrusta mediante la bandera de propiedad Font.IsEmbedded = true; Por supuesto es posible leer esta propiedad inmediatamente después de establecerla, pero no es un enfoque conveniente. La bandera NotifyAboutFontEmbeddingError impone un mecanismo de excepción para los casos en que el intento de incrustar la fuente falla. Si esta bandera está activada se lanzará una excepción del tipo Aspose::Pdf::FontEmbeddingException. Por defecto false en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.text/ifontoptions/set_notifyaboutfontembeddingerror/
---
## IFontOptions::set_NotifyAboutFontEmbeddingError method


A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo restricciones de licencia o cuando la fuente deseada no se encuentra en el equipo de destino. Cuando ocurre esta situación no es sencillo detectarla, porque la fuente deseada se incrusta mediante la bandera de propiedad Font.IsEmbedded = true; Por supuesto es posible leer esta propiedad inmediatamente después de establecerla, pero no es un enfoque conveniente. La bandera NotifyAboutFontEmbeddingError impone un mecanismo de excepción para los casos en que el intento de incrustar la fuente falla. Si esta bandera está activada se lanzará una excepción del tipo [Aspose::Pdf::FontEmbeddingException](../../../aspose.pdf/fontembeddingexception/). Por defecto false.

```cpp
virtual void Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError(bool value)=0
```

## Ver también

* Class [IFontOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
