---
title: Class ComboBoxField
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Forms.ComboBoxField. Clase que representa el campo Combobox del formulario
type: docs
weight: 5000
url: /es/net/aspose.pdf.forms/comboboxfield/
---
## Clase ComboBoxField

Clase que representa el campo Combobox del formulario.

```csharp
public class ComboBoxField : ChoiceField
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ComboBoxField](comboboxfield/#constructor)() | Constructor para ComboBoxField que se utilizará en el Generador. |
| [ComboBoxField](comboboxfield/#constructor_1)(Document) | Crea un campo CombBox para trabajar con el Generador. |
| [ComboBoxField](comboboxfield/#constructor_2)(Document, Rectangle) | Constructor para el campo Combobox. |
| [ComboBoxField](comboboxfield/#constructor_3)(Page, Rectangle) | Constructor para el campo Combobox. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Obtiene las acciones de la anotación. (2 propiedades) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtiene o establece el estado de apariencia actual de la anotación. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Obtiene o establece el nombre alternativo del campo (Un nombre de campo alternativo que se utilizará en lugar del nombre real del campo donde se identifique el campo en la interfaz de usuario). El nombre alternativo se utiliza como tooltip del campo en Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Obtiene o establece el índice de esta anotación en la página. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtiene o establece las características del borde de la anotación. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtiene o establece el color de la anotación. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Obtiene o establece la bandera de compromiso en el cambio de selección. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtiene o establece el texto de la anotación. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Obtiene el número de subcampos en este campo. (Por ejemplo, el número de elementos en el campo de botón de opción). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Obtiene o establece la apariencia predeterminada del campo. |
| [Editable](../../aspose.pdf.forms/comboboxfield/editable/) { get; set; } | Obtiene o establece el estado editable del campo. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Obtiene o establece la bandera exportable del campo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Banderas de la anotación. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtiene el nombre completamente calificado de la anotación. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtiene o establece la altura de la anotación. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Modo de resaltado de la anotación. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo de fragmento (para el generador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para la generación de pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Obtiene o establece un valor booleano que indica si este campo es un campo no terminal, es decir, un grupo de campos. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para la generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para la generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para la generación de pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Propiedad para soporte de Generador. Se utiliza cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Devuelve verdadero si el diccionario está sincronizado. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Obtiene el subcampo contenido en este campo por el nombre del subcampo. (2 indexadores) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Obtiene o establece el nombre de mapeo del campo que se utilizará al exportar datos del campo de formulario interactivo desde el documento. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtiene o establece la fecha y hora en que se modificó recientemente la anotación. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Obtiene o establece la bandera de multiselección. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtiene o establece el nombre de la anotación en la página. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Una acción que se realizará cuando se active la anotación. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Obtiene la colección de opciones de elección. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Obtiene el índice de la página que contiene este campo. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Obtiene el padre de la anotación. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Obtiene o establece el nombre parcial del campo. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Obtiene o establece el estado de solo lectura del campo. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Obtiene o establece el rectángulo del campo. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Obtiene o establece el estado requerido del campo. |
| virtual [Selected](../../aspose.pdf.forms/choicefield/selected/) { get; set; } | Obtiene o establece el índice de la opción seleccionada. Esta propiedad permite cambiar la selección. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | Obtiene o establece un array de elementos seleccionados. Para una lista de multiselección, el array contiene más de un elemento. Para una lista de selección única, contiene un solo elemento. |
| [SpellCheck](../../aspose.pdf.forms/comboboxfield/spellcheck/) { get; set; } | Obtiene o establece el estado de actividad de verificación ortográfica. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Objeto de sincronización. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Obtiene o establece el orden de tabulación del campo. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Obtiene o establece el valor del campo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Acepta al visitante. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string) | Agrega una nueva opción con el nombre especificado. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | Agrega una nueva opción con el valor de exportación y el nombre especificados. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Actualiza los parámetros y la apariencia, de acuerdo con la transformación de la matriz. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instancia. Método virtual. Siempre devuelve null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Copia los subcampos de este campo en un array comenzando desde el índice especificado. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Elimina la opción por su nombre. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Ejecuta una acción de JavaScript especificada para el campo. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporta el campo de formulario PDF especificado a formato JSON y escribe el resultado en el flujo proporcionado. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporta el campo de formulario PDF especificado a formato JSON y escribe el resultado en el archivo especificado. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporta el contenido del campo especificado en un flujo JSON. Los valores del campo de botón no se exportan. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Elimina este campo y coloca su valor directamente en la página. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Devuelve el nombre del estado "marcado" de acuerdo con los nombres de estado existentes. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Devuelve el enumerador de los campos contenidos. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importa datos en los campos especificados desde un flujo JSON, basado en una coincidencia exacta de los nombres completos de los campos. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importa datos en el campo especificado desde un flujo JSON, utilizando el nombre completo especificado en la variable 'fieldFullNameInJSON' para la coincidencia. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Recalcula todos los campos calculados en el formulario. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Establece la posición del campo. |

### Ver También

* clase [ChoiceField](../choicefield/)
* espacio de nombres [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../)