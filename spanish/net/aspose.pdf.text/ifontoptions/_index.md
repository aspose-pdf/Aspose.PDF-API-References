---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Interfaz Aspose.Pdf.Text.IFontOptions. Propiedades útiles para ajustar el comportamiento de la fuente
type: docs
weight: 10610
url: /es/net/aspose.pdf.text/ifontoptions/
---
## Interfaz IFontOptions

Propiedades útiles para ajustar el comportamiento de la fuente

```csharp
public interface IFontOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo, restricciones de licencia o cuando la fuente deseada no se encuentra en la computadora de destino. Cuando se presenta esta situación, no es fácil de detectar, porque la fuente deseada se incrusta a través del conjunto de la propiedad flag Font.IsEmbedded = true; Por supuesto, es posible leer esta propiedad inmediatamente después de que se haya establecido, pero no es un enfoque conveniente. La bandera NotifyAboutFontEmbeddingError impone un mecanismo de excepción para los casos en que el intento de incrustar la fuente falla. Si esta bandera está establecida, se lanzará una excepción del tipo [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/). Por defecto, falso. |

### Ver También

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)