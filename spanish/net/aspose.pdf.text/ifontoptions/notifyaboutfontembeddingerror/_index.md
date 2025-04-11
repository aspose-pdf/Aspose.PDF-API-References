---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: Propiedad IFontOptions. A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo, restricciones de licencia o cuando la fuente deseada no se encontró en la computadora de destino. Cuando esta situación ocurre, no es simple de detectar, porque la fuente deseada está incrustada a través de un conjunto de la propiedad flag Font.IsEmbedded = true; Por supuesto, es posible leer esta propiedad inmediatamente después de que se estableció, pero no es un enfoque conveniente. La bandera NotifyAboutFontEmbeddingError impone un mecanismo de excepción para los casos en que el intento de incrustar la fuente falla. Si esta bandera está establecida, se lanzará una excepción de tipo [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). Por defecto, falso.
type: docs
weight: 10
url: /es/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## Propiedad IFontOptions.NotifyAboutFontEmbeddingError

A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo, restricciones de licencia o cuando la fuente deseada no se encontró en la computadora de destino. Cuando esta situación ocurre, no es simple de detectar, porque la fuente deseada está incrustada a través de un conjunto de la propiedad flag Font.IsEmbedded = true; Por supuesto, es posible leer esta propiedad inmediatamente después de que se estableció, pero no es un enfoque conveniente. La bandera NotifyAboutFontEmbeddingError impone un mecanismo de excepción para los casos en que el intento de incrustar la fuente falla. Si esta bandera está establecida, se lanzará una excepción de tipo [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). Por defecto, falso.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Ver También

* interfaz [IFontOptions](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../../)