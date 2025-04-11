---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LoadOptionsResourceLoadingResult. Resultado de la carga personalizada de recursos
type: docs
weight: 6150
url: /es/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

Resultado de la carga personalizada de recursos

```csharp
public class ResourceLoadingResult
```

## Constructors

| Name | Description |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Crea una instancia del resultado de carga |

## Properties

| Name | Description |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Datos binarios que se cargaron con el cargador personalizado - deben establecerse después de la carga |

## Fields

| Name | Description |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | A veces, la codificación del recurso se conoce después o durante la carga. En tal caso, el código personalizado puede proporcionar al convertidor ese conocimiento a través de este parámetro. Puede dejar nulo este parámetro si la codificación es desconocida o no importa. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | A veces es imposible cargar el recurso solicitado por alguna razón. La falta de disponibilidad del recurso a menudo no conduce a un fallo de conversión y el documento resultante puede crearse de todos modos (pero tal vez en una calidad un poco peor, sin imágenes, etc.). Si ocurrió una excepción durante la carga, simplemente captúrela y colóquela en este parámetro; a veces esa información es útil para el convertidor para renderizar el resultado. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | A veces, por alguna razón, la carga no debe ocurrir en el código personalizado. En tal caso, establezca esta bandera como Verdadero. En tal caso, el convertidor intentará usar el cargador de recursos predeterminado interno para obtener ese resultado (como se comporta en situaciones cuando no se proporciona una estrategia personalizada). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | A veces, el conocimiento sobre el tipo MIME del recurso cargado es útil para el convertidor. Puede proporcionar el tipo MIME (si se conocía después de la carga) en este parámetro. Por favor, deje el parámetro igual a nulo cuando el tipo MIME es desconocido o no es necesario proporcionarlo. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)