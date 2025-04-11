---
title: Class WatermarkArtifact
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.WatermarkArtifact. La clase describe el artefacto de marca de agua. Esto puede ser utilizado para
type: docs
weight: 11310
url: /es/net/aspose.pdf/watermarkartifact/
---
## Clase WatermarkArtifact

La clase describe el artefacto de marca de agua. Esto puede ser utilizado para

```csharp
public class WatermarkArtifact : Artifact
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WatermarkArtifact](watermarkartifact/)() | Crea una instancia del artefacto de marca de agua. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Alineación horizontal del artefacto. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Alineación vertical del artefacto. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Margen inferior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Obtiene la colección de operadores internos del artefacto. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Obtiene el nombre del subtipo de artefacto. Puede ser utilizado si el subtipo de artefacto no es un subtipo estándar. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Obtiene el nombre del tipo de artefacto. Puede ser utilizado si el tipo de artefacto no es estándar. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Obtiene el XForm del artefacto (si se utiliza XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Obtiene la imagen del artefacto (si está presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Si es verdadero, el artefacto se coloca detrás del contenido de la página. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Margen izquierdo del artefacto. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Líneas del artefacto de texto multilínea. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Obtiene o establece la opacidad del artefacto. Los valores posibles están en el rango de 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Obtiene o establece la posición del artefacto. Si esta propiedad se especifica, entonces los márgenes y alineaciones se ignoran. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Obtiene el rectángulo del artefacto. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Margen derecho del artefacto. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Obtiene o establece el ángulo de rotación del artefacto. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Obtiene el subtipo del artefacto. Si el artefacto tiene un subtipo no estándar, el nombre del subtipo puede ser leído a través de CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Obtiene el texto del artefacto. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Estado del texto para el texto del artefacto. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Margen superior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Obtiene el tipo de artefacto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Inicia actualizaciones retrasadas. Utiliza esta función si necesitas hacer varios cambios en el mismo artefacto para mejorar el rendimiento. Normalmente, los operadores del artefacto se cambian cada vez que se cambia una propiedad del artefacto. Esto provoca un cambio en el contenido de la página cada vez que se cambia el artefacto. Para evitar este efecto, coloca todas las actualizaciones del artefacto entre las llamadas a StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Desecha el artefacto. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Obtiene el valor personalizado del artefacto. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Elimina el valor personalizado del artefacto. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Guarda todas las actualizaciones en el artefacto que se realizaron después de la llamada a BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Establece la imagen del artefacto. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Establece la imagen del artefacto. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Establece el texto y las propiedades de texto del artefacto. Permite especificar múltiples líneas. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Establece qué cadena será reemplazada por el número de página. El valor predeterminado es #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Establece la página PDF que se coloca en la página del documento como artefacto. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Establece el texto del artefacto. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Establece el texto y las propiedades de texto del artefacto. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Establece el valor personalizado del artefacto. |

### Ver También

* clase [Artifact](../artifact/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)