---
title: "Clase Aspose::Pdf::Artifact"
linktitle: "Artefacto"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Artifact. La clase representa un objeto Artifact de PDF en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf/artifact/
---
## Artifact class


La clase representa un objeto PDF [Artifact](./).

```cpp
class Artifact : public System::IDisposable
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [ArtifactSubtype](./artifactsubtype/) | Enumeración de los posibles subtipos de artefactos. |
| [ArtifactType](./artifacttype/) | Enumeración de los posibles tipos de artefactos. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Artifact](./artifact/)(const System::String\&, const System::String\&) | Constructor de artefacto con tipo y subtipo especificados. |
| [Artifact](./artifact/)(Artifact::ArtifactType, Artifact::ArtifactSubtype) | Constructor de artefacto con tipo y subtipo especificados. |
| [BeginUpdates](./beginupdates/)() | Inicie actualizaciones retrasadas. Use esta función si necesita realizar varios cambios al mismo artefacto para mejorar el rendimiento. Normalmente los operadores del artefacto se modifican cada vez que se cambia una propiedad del artefacto. Esto provoca la modificación del contenido de la página cada vez que el artefacto se cambia. Para evitar este efecto, coloque todas las actualizaciones del artefacto entre las llamadas StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez. |
| [Dispose](./dispose/)() override | Dispose el artefacto. |
| [get_ArtifactHorizontalAlignment](./get_artifacthorizontalalignment/)() const | Alineación horizontal del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [get_ArtifactVerticalAlignment](./get_artifactverticalalignment/)() const | Alineación vertical del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [get_BottomMargin](./get_bottommargin/)() const | Margen inferior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [get_Contents](./get_contents/)() | Obtiene la colección de operadores internos del artefacto. |
| [get_CustomSubtype](./get_customsubtype/)() | Obtiene el nombre del subtipo del artefacto. Puede usarse si el subtipo del artefacto no es un subtipo estándar. |
| [get_CustomType](./get_customtype/)() | Obtiene el nombre del tipo de artefacto. Puede usarse si el tipo de artefacto no es estándar. |
| [get_Form](./get_form/)() | Obtiene el [XForm](../xform/) del artefacto (si se usa el [XForm](../xform/)). |
| [get_Image](./get_image/)() | Obtiene la imagen del artefacto (si está presente). |
| [get_IsBackground](./get_isbackground/)() const | Si es verdadero, el [Artifact](./) se coloca detrás del contenido de la página. |
| [get_LeftMargin](./get_leftmargin/)() const | Margen [Left](../left/) del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [get_Lines](./get_lines/)() | Líneas del artefacto de texto multilínea. |
| [get_Opacity](./get_opacity/)() const | Obtiene la opacidad del artefacto. Los valores posibles están en el rango 0..1. |
| [get_Position](./get_position/)() const | Obtiene la posición del artefacto. Si se especifica esta propiedad, entonces los márgenes y alineaciones se ignoran. |
| [get_Rectangle](./get_rectangle/)() | Obtiene el rectángulo del artefacto. |
| [get_RightMargin](./get_rightmargin/)() const | Margen [Right](../right/) del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [get_Rotation](./get_rotation/)() | Obtiene el ángulo de rotación del artefacto. |
| [get_Subtype](./get_subtype/)() | Obtiene el subtipo del artefacto. Si el artefacto tiene un subtipo no estándar, el nombre del subtipo puede leerse mediante CustomSubtype. |
| [get_Text](./get_text/)() | Obtiene el texto del artefacto. |
| [get_TextState](./get_textstate/)() | Estado [Text](../../aspose.pdf.text/) para el texto del artefacto. |
| [get_TopMargin](./get_topmargin/)() const | Margen superior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [get_Type](./get_type/)() | Obtiene el tipo de artefacto. |
| [GetValue](./getvalue/)(const System::String\&) | Obtiene el valor personalizado del artefacto. |
| [RemoveValue](./removevalue/)(const System::String\&) | Elimina el valor personalizado del artefacto. |
| [SaveUpdates](./saveupdates/)() | Guarda todas las actualizaciones en el artefacto que se realizaron después de la llamada a [BeginUpdates()](./beginupdates/). |
| [set_ArtifactHorizontalAlignment](./set_artifacthorizontalalignment/)(HorizontalAlignment) | Alineación horizontal del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [set_ArtifactVerticalAlignment](./set_artifactverticalalignment/)(VerticalAlignment) | Alineación vertical del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [set_BottomMargin](./set_bottommargin/)(double) | Margen inferior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [set_CustomSubtype](./set_customsubtype/)(const System::String\&) | Obtiene el nombre del subtipo del artefacto. Puede usarse si el subtipo del artefacto no es un subtipo estándar. |
| [set_CustomType](./set_customtype/)(const System::String\&) | Obtiene el nombre del tipo de artefacto. Puede usarse si el tipo de artefacto no es estándar. |
| [set_IsBackground](./set_isbackground/)(bool) | Si es verdadero, el [Artifact](./) se coloca detrás del contenido de la página. |
| [set_LeftMargin](./set_leftmargin/)(double) | Margen [Left](../left/) del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [set_Opacity](./set_opacity/)(double) | Establece la opacidad del artefacto. Los valores posibles están en el rango 0..1. |
| [set_Position](./set_position/)(const System::SharedPtr\<Point\>\&) | Establece la posición del artefacto. Si se especifica esta propiedad, los márgenes y alineaciones se ignoran. |
| [set_RightMargin](./set_rightmargin/)(double) | Margen [Right](../right/) del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [set_Rotation](./set_rotation/)(double) | Establece el ángulo de rotación del artefacto. |
| [set_Subtype](./set_subtype/)(Artifact::ArtifactSubtype) | Obtiene el subtipo del artefacto. Si el artefacto tiene un subtipo no estándar, el nombre del subtipo puede leerse mediante CustomSubtype. |
| [set_Text](./set_text/)(const System::String\&) | Obtiene el texto del artefacto. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Estado [Text](../../aspose.pdf.text/) para el texto del artefacto. |
| [set_TopMargin](./set_topmargin/)(double) | Margen superior del artefacto. Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| [set_Type](./set_type/)(Artifact::ArtifactType) | Obtiene el tipo de artefacto. |
| [SetImage](./setimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece la imagen del artefacto. |
| [SetImage](./setimage/)(const System::String\&) | Establece la imagen del artefacto. |
| [SetLinesAndState](./setlinesandstate/)(const System::ArrayPtr\<System::String\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Establece el texto y las propiedades de texto del artefacto. Permite especificar varias líneas. |
| [SetPageNumberReplacementString](./setpagenumberreplacementstring/)(const System::String\&) | Establece qué cadena se reemplazará con el número de página. El valor predeterminado es #. |
| [SetPdfPage](./setpdfpage/)(const System::SharedPtr\<Page\>\&) | Establece la página PDF que se coloca en la página del documento como artefacto. |
| [SetText](./settext/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Establece el texto del artefacto. |
| [SetTextAndState](./settextandstate/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Establece el texto y las propiedades de texto del artefacto. |
| [SetValue](./setvalue/)(const System::String\&, const System::String\&) | Establece el valor personalizado del artefacto. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
