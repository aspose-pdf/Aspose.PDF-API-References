---
title: "Aspose::Pdf::Forms::Field clase"
linktitle: "Campo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::Field clase. Clase base para campos de formulario Acro en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.forms/field/
---
## Field class


Clase base para campos de formulario Acro.

```cpp
class Field : public Aspose::Pdf::Annotations::WidgetAnnotation,
              public System::Collections::Generic::ICollection<System::SharedPtr<Annotations::WidgetAnnotation>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<Field\>\>\&, int32_t) | Copia los subcampos de este campo en una matriz comenzando desde el índice especificado. |
| [CopyToWidgetArray](./copytowidgetarray/)(const System::ArrayPtr\<System::SharedPtr\<Annotations::WidgetAnnotation\>\>\&, int32_t) | Copia los subcampos de este campo en una matriz comenzando desde el índice especificado. |
| [ExecuteFieldJavaScript](./executefieldjavascript/)(const System::SharedPtr\<Annotations::JavascriptAction\>\&) | Ejecuta una acción JavaScript especificada para el campo. |
| [Field](./field/)(const System::SharedPtr\<Document\>\&) | Crea un campo para su uso en Generator. |
| [Flatten](./flatten/)() override | Elimina este campo y coloca su valor directamente en la página. |
| [get_AlternateName](./get_alternatename/)() | Obtiene el nombre alternativo del campo (Un nombre de campo alternativo que se debe usar en lugar del nombre real del campo dondequiera que el campo deba identificarse en la interfaz de usuario). El nombre alternativo se usa como información sobre herramienta del campo en Adobe Acrobat. |
| [get_AnnotationIndex](./get_annotationindex/)() | Obtiene el índice de esta anotación en la página. |
| [get_Count](./get_count/)() const override | Obtiene el número de subcampos en este campo. (Por ejemplo, número de elementos en un campo de botón de opción). |
| static [get_FitIntoRectangle](./get_fitintorectangle/)() | Si es verdadero, el tamaño de fuente se reducirá para ajustar el texto al rectángulo especificado. |
| [get_IsGroup](./get_isgroup/)() const | Obtiene el valor booleano que indica si este campo es un campo no terminal, es decir, un grupo de campos. |
| [get_IsSharedField](./get_issharedfield/)() const | Propiedad para soporte de Generator. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una sola vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento. |
| [get_IsSynchronized](./get_issynchronized/)() | Devuelve verdadero si el diccionario está sincronizado. |
| [get_MappingName](./get_mappingname/)() | Obtiene el nombre de mapeo del campo que se debe usar al exportar datos de campos de formulario interactivo del documento. |
| static [get_MaxFontSize](./get_maxfontsize/)() | Tamaño máximo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| static [get_MinFontSize](./get_minfontsize/)() | Tamaño mínimo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| [get_PageIndex](./get_pageindex/)() override | Obtiene el índice de la página que contiene este campo. |
| [get_PartialName](./get_partialname/)() | Obtiene el nombre parcial del campo. |
| [get_Rect](./get_rect/)() override | Obtiene el rectángulo del campo. |
| [get_SyncRoot](./get_syncroot/)() const | Objeto de sincronización. |
| [get_TabOrder](./get_taborder/)() | Obtiene el orden de tabulación del campo. |
| virtual [get_Value](./get_value/)() | Obtiene el valor del campo. |
| [GetEnumerator](./getenumerator/)() override | Devuelve el enumerador de los campos contenidos. |
| [idx_get](./idx_get/)(const System::String\&) | Obtiene el subcampo contenido en este campo por el nombre del subcampo. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el subcampo contenido en este campo por índice. |
| [Recalculate](./recalculate/)() | Recalcula todos los campos calculados en el formulario. |
| [set_AlternateName](./set_alternatename/)(const System::String\&) | Establece el nombre alternativo del campo (Un nombre alternativo del campo que se utilizará en lugar del nombre real del campo dondequiera que el campo deba identificarse en la interfaz de usuario). El nombre alternativo se usa como información sobre herramientas del campo en Adobe Acrobat. |
| [set_AnnotationIndex](./set_annotationindex/)(int32_t) | Establece el índice de esta anotación en la página. |
| static [set_FitIntoRectangle](./set_fitintorectangle/)(bool) | Si es verdadero, el tamaño de fuente se reducirá para ajustar el texto al rectángulo especificado. |
| [set_IsSharedField](./set_issharedfield/)(bool) | Propiedad para soporte de Generator. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una sola vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento. |
| [set_MappingName](./set_mappingname/)(const System::String\&) | Establece el nombre de mapeo del campo que se utilizará al exportar los datos de campos de formulario interactivo del documento. |
| static [set_MaxFontSize](./set_maxfontsize/)(double) | Tamaño máximo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| static [set_MinFontSize](./set_minfontsize/)(double) | Tamaño mínimo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| [set_PartialName](./set_partialname/)(const System::String\&) | Establece el nombre parcial del campo. |
| [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) override | Establece el rectángulo del campo. |
| [set_TabOrder](./set_taborder/)(int32_t) | Establece el orden de tabulación del campo. |
| virtual [set_Value](./set_value/)(System::String) | Establece el valor del campo. |
| virtual [SetPosition](./setposition/)(System::SharedPtr\<Point\>) | Establece la posición del campo. |
## Ver también

* Class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
