---
title: IFontOptions
second_title: Referencia de API de Aspose.PDF para .NET
description: Propiedades útiles para ajustar el comportamiento de la fuente
type: docs
weight: 6790
url: /es/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

Propiedades útiles para ajustar el comportamiento de la fuente

```csharp
public interface IFontOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror) { get; set; } | A veces no es posible incrustar la fuente deseada en el documento. Hay muchas razones, por ejemplo restricciones de licencia o cuando no se encontró la fuente deseada en la computadora de destino. Cuando se presenta esta situación, no es simplemente para detectar, porque la fuente deseada está incrustada a través del conjunto del indicador de propiedad Font.IsEmbedded = true; Por supuesto, es posible leer esta propiedad inmediatamente después de establecerla, pero no es un enfoque conveniente. Marcar NotifyAboutFontEmbeddingError aplica el mecanismo de excepción para los casos en los que falló el intento de incrustar la fuente. Si este indicador se establece una excepción de type [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception) será arrojado. Por defecto false. |

### Ver también

* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->