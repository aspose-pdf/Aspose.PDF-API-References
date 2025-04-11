---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Artifact. La clase representa el objeto Artifact de PDF
type: docs
weight: 2770
url: /es/net/aspose.pdf/artifact/
---
## Clase Artifact

La clase representa el objeto Artifact de PDF.

```csharp
public class Artifact : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | Constructor de artifact con tipo y subtipo especificados |
| [Artifact](artifact/#constructor_1)(string, string) | Constructor de artifact con tipo y subtipo especificados |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Alineación horizontal del artifact. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Alineación vertical del artifact. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Margen inferior del artifact. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Obtiene la colección de operadores internos del artifact. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Obtiene el nombre del subtipo de artifact. Puede ser utilizado si el subtipo de artifact no es un subtipo estándar. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Obtiene el nombre del tipo de artifact. Puede ser utilizado si el tipo de artifact no es estándar. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Obtiene el XForm del artifact (si se utiliza XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Obtiene la imagen del artifact (si está presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Si es verdadero, el Artifact se coloca detrás del contenido de la página. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Margen izquierdo del artifact. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Líneas del artifact de texto multilinea. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Obtiene o establece la opacidad del artifact. Los valores posibles están en el rango de 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Obtiene o establece la posición del artifact. Si esta propiedad se especifica, entonces los márgenes y alineaciones se ignoran. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Obtiene el rectángulo del artifact. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Margen derecho del artifact. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Obtiene o establece el ángulo de rotación del artifact. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Obtiene el subtipo del artifact. Si el artifact tiene un subtipo no estándar, el nombre del subtipo puede ser leído a través de CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Obtiene el texto del artifact. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Estado del texto para el texto del artifact. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Margen superior del artifact. Si la posición se especifica explícitamente (en la propiedad Position), este valor se ignora. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Obtiene el tipo de artifact. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Comienza las actualizaciones retrasadas. Utiliza esta función si necesitas hacer varios cambios en el mismo artifact para mejorar el rendimiento. Normalmente, los operadores del artifact se cambian cada vez que se cambia una propiedad del artifact. Esto causa que el contenido de la página cambie cada vez que se modifica el artifact. Para evitar este efecto, coloca todas las actualizaciones del artifact entre las llamadas a StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Desecha el artifact. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Obtiene el valor personalizado del artifact. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Elimina el valor personalizado del artifact. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Guarda todas las actualizaciones en el artifact que se realizaron después de la llamada a BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | Establece la imagen del artifact. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | Establece la imagen del artifact. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Establece el texto y las propiedades del texto del artifact. Permite especificar múltiples líneas. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Establece qué cadena será reemplazada por el número de página. El valor predeterminado es #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Establece la página PDF que se coloca en la página del documento como artifact. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Establece el texto del artifact. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Establece el texto y las propiedades del texto del artifact. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Establece el valor personalizado del artifact. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | Enumeración de posibles subtipos de artifacts. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | Enumeración de posibles tipos de artifacts. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)