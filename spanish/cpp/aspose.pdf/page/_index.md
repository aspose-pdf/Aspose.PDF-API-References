---
title: "Clase Aspose::Pdf::Page"
linktitle: "Página"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Page. Clase que representa una página de un documento PDF en C++."
type: docs
weight: 13000
url: /es/cpp/aspose.pdf/page/
---
## Page class


Clase que representa una página de un documento PDF.

```cpp
class Page : public System::IDisposable,
             public Aspose::Pdf::ISupportsMemoryCleanup,
             public Aspose::Pdf::IOperatorContainer
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Annotations::AnnotationSelector\>\&) | Acepta el objeto visitante [AnnotationSelector](../) que proporciona funcionalidad para trabajar con anotaciones. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Text::TextFragmentAbsorber\>\&) | Acepta el objeto visitante **TextFragmentAbsorber** que proporciona funcionalidad para trabajar con objetos de texto. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::ImagePlacementAbsorber\>\&) | Acepta el objeto visitante [ImagePlacementAbsorber](../imageplacementabsorber/) que proporciona funcionalidad para trabajar con objetos de colocación de imágenes. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Text::TextAbsorber\>\&) | Acepta el objeto visitante **TextAbsorber** que proporciona funcionalidad para trabajar con objetos de texto. |
| [AddGraphics](./addgraphics/)(const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Agrega gráficos a la página. Funciona más rápido que agregar elementos uno por uno con el método [GraphicElement::AddOnPage(Page)](../). |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) | Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [AddImage](./addimage/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<Aspose::Pdf::Rectangle\>, int32_t, int32_t, bool, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Agrega una imagen a la página y la coloca según la posición del rectángulo de la imagen. |
| [AddImage](./addimage/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen. |
| [AddStamp](./addstamp/)(const System::SharedPtr\<Aspose::Pdf::Stamp\>\&) | Coloca un sello en la página. [Stamp](../stamp/) puede ser número de página, imagen o texto simple, por ejemplo, algún logotipo. |
| [AsByteArray](./asbytearray/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Convierte la página actual a mapa de bits y luego devuelve una matriz de bytes. |
| [AsXml](./asxml/)() | Convierte la página actual a xml con codificación utf8. |
| [CalculateContentBBox](./calculatecontentbbox/)() | Calcula el valor bbox - rectángulo que contiene el contenido sin márgenes visibles. |
| [ConvertToPNGMemoryStream](./converttopngmemorystream/)() | Convierte la página a PNG para el flujo de imágenes DSR, OMR, OCR. |
| [DeleteGraphics](./deletegraphics/)(const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\&) | Elimina los gráficos de la página. Funciona más rápido que eliminar los elementos uno por uno con el método [GraphicElement::Remove](../). |
| [Dispose](./dispose/)() override | Libera memoria. |
| [Flatten](./flatten/)() | Elimina todos los campos ubicados en la página y coloca sus valores en su lugar. |
| [FreeMemory](./freememory/)() override | Borra los datos en caché. |
| [get_Actions](./get_actions/)() | Obtiene la colección de propiedades de la página. |
| [get_Annotations](./get_annotations/)() | Obtiene la colección de anotaciones de la página. [Annotations](../../aspose.pdf.annotations/) |
| [get_ArtBox](./get_artbox/)() | Obtiene el art box de la página. |
| [get_Artifacts](./get_artifacts/)() | Obtiene la colección de artefactos en la página. |
| [get_Background](./get_background/)() | Obtiene el color de fondo de la página. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Obtiene la imagen de fondo para la página (solo para el generador, no se rellena al leer el documento). |
| [get_BleedBox](./get_bleedbox/)() | Obtiene el bleed box de la página. |
| [get_ColorType](./get_colortype/)() | Establece el tipo de color de las páginas basado en la información obtenida de los operadores SetColor, imágenes y formularios. |
| [get_Contents](./get_contents/)() override | Obtiene la colección de operadores en el flujo de contenido de la página. [OperatorCollection](../operatorcollection/) |
| [get_CropBox](./get_cropbox/)() | Obtiene el crop box de la página. |
| [get_Duration](./get_duration/)() | Obtiene o establece la duración de visualización de la página. Este es el tiempo en segundos que la página debe mostrarse durante la presentación. Devuelve -1 si la duración no está definida. |
| [get_FieldsInTabOrder](./get_fieldsintaborder/)() | Obtiene la lista de objetos Field en orden de tabulación en esta página. |
| [get_Footer](./get_footer/)() const | Obtiene el pie de página. |
| [get_Group](./get_group/)() | Obtiene una clase de atributos de grupo que especifica los atributos del grupo de página para su uso en el modelo de imágenes transparentes. |
| [get_Header](./get_header/)() const | Obtiene el encabezado de la página. |
| [get_IsAddParagraphsAfterLast](./get_isaddparagraphsafterlast/)() const | Obtiene la adición de párrafos después del último párrafo de la página. |
| [get_Layers](./get_layers/)() | Obtiene la colección de capas. |
| [get_MediaBox](./get_mediabox/)() | Obtiene el media box de la página. |
| [get_NoteLineStyle](./get_notelinestyle/)() | Obtiene el estilo de línea para notas. (solo para generador, no se rellena al leer el documento) |
| [get_Number](./get_number/)() | Obtiene el número de la página. |
| [get_PageInfo](./get_pageinfo/)() | Obtiene la información de la página (solo para generador, no se rellena al leer el documento). |
| [get_Paragraphs](./get_paragraphs/)() | Obtiene los párrafos. |
| [get_Rect](./get_rect/)() | Obtiene el rectángulo de la página. Para obtener: se devuelve el recorte de la página si se especifica, de lo contrario se devuelve la caja de medios de la página. Para establecer: siempre se establece la caja de medios de la página. Tenga en cuenta que esta propiedad no considera la rotación de la página. Para obtener el rectángulo de la página considerando la rotación, utilice ActualRect. |
| [get_Resources](./get_resources/)() override | Obtiene los recursos de la página. El objeto [Resources](../resources/) contiene colecciones de imágenes, formularios y fuentes. [Resources](../resources/) |
| [get_Rotate](./get_rotate/)() | Obtiene la rotación de la página. |
| [get_RotationMatrix](./get_rotationmatrix/)() | Obtiene la matriz de transformación para la página. |
| [get_TabOrder](./get_taborder/)() | Obtiene el orden de tabulación de la página. Valores posibles: [Row](../row/), Column. Predeterminado, Manual. |
| [get_TocInfo](./get_tocinfo/)() const | Obtiene la información del índice. |
| [get_TrimBox](./get_trimbox/)() | Obtiene la trim box de la página. |
| [get_UserUnit](./get_userunit/)() | Obtiene el valor UserUnit. Un número positivo que indica el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1/72 de pulgada. El valor predeterminado es 1. Por favor, establezca cero o un valor negativo para borrar esta entrada en la página. |
| [get_Watermark](./get_watermark/)() | Obtiene la marca de agua de la página. |
| [GetNotifications](./getnotifications/)() | Devuelve notificaciones sobre operaciones internas con el contenido de la página. (Solo se admiten notificaciones sobre eventos de párrafo en escenarios de adición de texto por ahora.) |
| [GetPageRect](./getpagerect/)(bool) | Devuelve el rectángulo de la página según su CropBox (o MediaBox si CropBox es nulo). |
| [GetResources](./getresources/)() override | Recupera los recursos asociados con la página. |
| [HasVectorGraphics](./hasvectorgraphics/)() | Detecta la presencia de gráficos vectoriales, si están presentes en la página. |
| static [IntToRotation](./inttorotation/)(int32_t) | Traduce el valor entero al miembro correspondiente de la enumeración de rotación. |
| [IsBlank](./isblank/)(double) | Obtiene la bandera que indica si la página está en blanco o no. |
| [MakeGrayscale](./makegrayscale/)() | Convierte la página a escala de grises. |
| [MergeLayers](./mergelayers/)(const System::String\&) | Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado. |
| [MergeLayers](./mergelayers/)(const System::String\&, const System::String\&) | Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado y el grupo de contenido opcional [Id](../id/). |
| [Resize](./resize/)(System::SharedPtr\<Aspose::Pdf::PageSize\>) | Redimensiona la página. |
| static [RotationToInt](./rotationtoint/)(Aspose::Pdf::Rotation) | Traduce el miembro de la enumeración de rotación a un valor entero. |
| [SendTo](./sendto/)(const System::SharedPtr\<Aspose::Pdf::Devices::PageDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Envía la página a procesar con el dispositivo de página dado. |
| [SendTo](./sendto/)(const System::SharedPtr\<Aspose::Pdf::Devices::PageDevice\>\&, const System::String\&) | Envía la página a procesar con el dispositivo de página dado. |
| [set_ArtBox](./set_artbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece la art box de la página. |
| [set_Background](./set_background/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Establece el color de fondo de la página. |
| [set_BackgroundImage](./set_backgroundimage/)(const System::SharedPtr\<Aspose::Pdf::Image\>\&) | Establece la imagen de fondo para la página (solo para el generador, no se rellena al leer el documento). |
| [set_BleedBox](./set_bleedbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece la bleed box de la página. |
| [set_CropBox](./set_cropbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece la crop box de la página. |
| [set_Duration](./set_duration/)(double) | Obtiene o establece la duración de visualización de la página. Este es el tiempo en segundos que la página debe mostrarse durante la presentación. Devuelve -1 si la duración no está definida. |
| [set_Footer](./set_footer/)(const System::SharedPtr\<Aspose::Pdf::HeaderFooter\>\&) | Establece el pie de página. |
| [set_Group](./set_group/)(const System::SharedPtr\<Aspose::Pdf::Group\>\&) | Establece una clase de atributos de grupo que especifica los atributos del grupo de página de la página para su uso en el modelo de imágenes transparentes. |
| [set_Header](./set_header/)(const System::SharedPtr\<Aspose::Pdf::HeaderFooter\>\&) | Establece el encabezado de la página. |
| [set_IsAddParagraphsAfterLast](./set_isaddparagraphsafterlast/)(bool) | Establece la adición de párrafos después del último párrafo de la página. |
| [set_Layers](./set_layers/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Layer\>\>\>\&) | Establece la colección de capas. |
| [set_MediaBox](./set_mediabox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece la caja de medios de la página. |
| [set_NoteLineStyle](./set_notelinestyle/)(const System::SharedPtr\<Aspose::Pdf::GraphInfo\>\&) | Establece el estilo de línea para notas. (solo para generador, no se completa al leer el documento) |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Establece la información de la página (solo para generador, no se completa al leer el documento). |
| [set_Paragraphs](./set_paragraphs/)(const System::SharedPtr\<Aspose::Pdf::Paragraphs\>\&) | Obtiene los párrafos. |
| [set_Rect](./set_rect/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece el rectángulo de la página. Para obtener: se devuelve la caja de recorte de la página si está especificada, de lo contrario se devuelve la caja de medios de la página. Para establecer: la caja de medios de la página siempre se establece. Tenga en cuenta que esta propiedad no considera la rotación de la página. Para obtener el rectángulo de la página considerando la rotación, por favor use ActualRect. |
| [set_Rotate](./set_rotate/)(Aspose::Pdf::Rotation) | Establece la rotación de la página. |
| [set_TabOrder](./set_taborder/)(Aspose::Pdf::TabOrder) | Establece el orden de pestañas de la página. Valores posibles: [Row](../row/), Column. Predeterminado, Manual. |
| [set_TocInfo](./set_tocinfo/)(const System::SharedPtr\<Aspose::Pdf::TocInfo\>\&) | Establece la información del índice. |
| [set_TrimBox](./set_trimbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Establece la caja de recorte de la página. |
| [set_UserUnit](./set_userunit/)(double) | Establece el valor de UserUnit. Un número positivo que indica el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1/72 de pulgada. El valor predeterminado es 1. Por favor, establezca cero o un valor negativo para borrar esta entrada en la página. |
| [set_Watermark](./set_watermark/)(const System::SharedPtr\<Aspose::Pdf::Watermark\>\&) | Establece la marca de agua de la página. |
| [SetPageSize](./setpagesize/)(double, double) | Establece el tamaño de la página. |
| [TrySaveVectorGraphics](./trysavevectorgraphics/)(const System::String\&) | Intenta guardar los gráficos vectoriales si están presentes en la página. El formato de guardado es SVG. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BeforePageGenerate](./beforepagegenerate/) | Procedimiento para personalizar el encabezado y el pie de página. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Class [IOperatorContainer](../ioperatorcontainer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
