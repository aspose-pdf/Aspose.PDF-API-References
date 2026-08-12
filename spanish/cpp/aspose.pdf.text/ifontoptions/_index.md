---
title: "Aspose::Pdf::Text::IFontOptions class"
linktitle: "IFontOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::IFontOptions class. Propiedades útiles para ajustar el comportamiento de Font en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf.text/ifontoptions/
---
## IFontOptions class


Propiedades útiles para ajustar el comportamiento de [Font](../font/).

```cpp
class IFontOptions : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_NotifyAboutFontEmbeddingError](./get_notifyaboutfontembeddingerror/)() | A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo restricciones de licencia o que la fuente deseada no se encuentre en el equipo de destino. Cuando ocurre esta situación no es sencillo detectarla, porque la fuente deseada se incrusta mediante la bandera de propiedad Font.IsEmbedded = true; Por supuesto es posible leer esta propiedad inmediatamente después de establecerla, pero no es un enfoque conveniente. La bandera NotifyAboutFontEmbeddingError aplica un mecanismo de excepción para los casos en que el intento de incrustar la fuente falla. Si esta bandera está activada se lanzará una excepción del tipo [Aspose::Pdf::FontEmbeddingException](../../aspose.pdf/fontembeddingexception/). Por defecto false. |
| virtual [set_NotifyAboutFontEmbeddingError](./set_notifyaboutfontembeddingerror/)(bool) | A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo restricciones de licencia o que la fuente deseada no se encuentre en el equipo de destino. Cuando ocurre esta situación no es sencillo detectarla, porque la fuente deseada se incrusta mediante la bandera de propiedad Font.IsEmbedded = true; Por supuesto es posible leer esta propiedad inmediatamente después de establecerla, pero no es un enfoque conveniente. La bandera NotifyAboutFontEmbeddingError aplica un mecanismo de excepción para los casos en que el intento de incrustar la fuente falla. Si esta bandera está activada se lanzará una excepción del tipo [Aspose::Pdf::FontEmbeddingException](../../aspose.pdf/fontembeddingexception/). Por defecto false. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
