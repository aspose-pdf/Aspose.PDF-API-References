---
title: Artifact
second_title: Referencia de API de Aspose.PDF para .NET
description: La clase representa el objeto PDF Artifact.
type: docs
weight: 1310
url: /es/net/aspose.pdf/artifact/
---
## Artifact class

La clase representa el objeto PDF Artifact.

```csharp
public class Artifact : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Artifact](artifact#constructor)(ArtifactType, ArtifactSubtype) | Constructor de artefacto con tipo y subtipo especificado |
| [Artifact](artifact#constructor_1)(string, string) | Constructor de artefacto con tipo y subtipo especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment) { get; set; } | Alineación horizontal del artefacto. Si la posición se especifica explícitamente (en la propiedad Posición), este valor se ignora. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment) { get; set; } | Alineación vertical del artefacto. Si la posición se especifica explícitamente (en la propiedad Posición), este valor se ignora. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin) { get; set; } | Margen inferior del artefacto. Si la posición se especifica explícitamente (en la propiedad Posición), este valor se ignora. |
| [Contents](../../aspose.pdf/artifact/contents) { get; } | Obtiene la colección de operadores internos de artefactos. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype) { get; set; } | Obtiene el nombre del subtipo de artefacto. Puede usarse si el subtipo de artefacto no es un subtipo estándar. |
| [CustomType](../../aspose.pdf/artifact/customtype) { get; set; } | Obtiene el nombre del tipo de artefacto. Puede usarse si el tipo de artefacto no es estándar. |
| [Form](../../aspose.pdf/artifact/form) { get; } | Obtiene XForm del artefacto (si se usa XForm). |
| [Image](../../aspose.pdf/artifact/image) { get; } | Obtiene la imagen del artefacto (si está presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground) { get; set; } | Si es verdadero Artefacto se coloca detrás del contenido de la página. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin) { get; set; } | Margen izquierdo del artefacto. Si la posición se especifica explícitamente (en la propiedad Posición), este valor se ignora. |
| [Lines](../../aspose.pdf/artifact/lines) { get; } | Líneas de artefacto de texto multilínea. |
| [Opacity](../../aspose.pdf/artifact/opacity) { get; set; } | Obtiene o establece la opacidad del artefacto. Los valores posibles están en el rango 0..1. |
| [Position](../../aspose.pdf/artifact/position) { get; set; } | Obtiene o establece la posición del artefacto. Si se especifica esta propiedad, se ignoran los márgenes y las alineaciones. |
| [Rectangle](../../aspose.pdf/artifact/rectangle) { get; } | Obtiene el rectángulo del artefacto. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin) { get; set; } | Margen derecho del artefacto. Si la posición se especifica explícitamente (en la propiedad Posición), este valor se ignora. |
| [Rotation](../../aspose.pdf/artifact/rotation) { get; set; } | Obtiene o establece el ángulo de rotación del artefacto. |
| [Subtype](../../aspose.pdf/artifact/subtype) { get; set; } | Obtiene el subtipo de artefacto. Si el artefacto tiene un subtipo no estándar, el nombre del subtipo se puede leer a través de CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text) { get; set; } | Obtiene el texto del artefacto. |
| [TextState](../../aspose.pdf/artifact/textstate) { get; set; } | Estado de texto para texto de artefacto. |
| [TopMargin](../../aspose.pdf/artifact/topmargin) { get; set; } | Margen superior del artefacto. Si la posición se especifica explícitamente (en la propiedad Posición), este valor se ignora. |
| [Type](../../aspose.pdf/artifact/type) { get; set; } | Obtiene el tipo de artefacto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates)() | Iniciar actualizaciones retrasadas. Utilice esta función si necesita realizar varios cambios en el mismo artefacto para mejorar el rendimiento. Por lo general, los operadores de artefactos se cambian en cualquier momento cuando se cambia la propiedad del artefacto. Esto provoca el cambio del contenido de la página cada vez que se cambia el artefacto. Para evitar este efecto, coloque todas las actualizaciones de artefactos entre las llamadas StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez. |
| [Dispose](../../aspose.pdf/artifact/dispose)() | Desechar el artefacto. |
| [GetValue](../../aspose.pdf/artifact/getvalue)(string) | Obtiene el valor personalizado del artefacto. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue)(string) | Eliminar valor personalizado del artefacto. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates)() | Guarda todas las actualizaciones en el artefacto que se realizaron después de la llamada BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage#setimage)(Stream) | Establece la imagen del artefacto. |
| [SetImage](../../aspose.pdf/artifact/setimage#setimage_1)(string) | Establece la imagen del artefacto. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate)(string[], TextState) | Establecer texto y propiedades de texto del artefacto. Permite especificar múltiples líneas. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage)(Page) | Establece la página PDF que se coloca en la página del documento como artefacto. |
| [SetText](../../aspose.pdf/artifact/settext)(FormattedText) | Establece el texto del artefacto. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate)(string, TextState) | Establecer texto y propiedades de texto del artefacto. |
| [SetValue](../../aspose.pdf/artifact/setvalue)(string, string) | Establece el valor personalizado del artefacto. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| enum [ArtifactSubtype](artifact.artifactsubtype) | Enumeración de posibles artefactos subtipo. |
| enum [ArtifactType](artifact.artifacttype) | Enumeración de posibles tipos de artefactos. |

### Ver también

* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
