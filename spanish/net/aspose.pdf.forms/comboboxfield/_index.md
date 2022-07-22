---
title: ComboBoxField
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase que representa el campo Combobox del formulario.
type: docs
weight: 2950
url: /es/net/aspose.pdf.forms/comboboxfield/
---
## ComboBoxField class

Clase que representa el campo Combobox del formulario.

```csharp
public class ComboBoxField : ChoiceField
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ComboBoxField](comboboxfield#constructor)() | Constructor para ComboBoxField para ser usado en Generator. |
| [ComboBoxField](comboboxfield#constructor_1)(Document) | Crea el campo CombBox para trabajar con Generator. |
| [ComboBoxField](comboboxfield#constructor_2)(Document, Rectangle) | Constructor para el campo Combobox. |
| [ComboBoxField](comboboxfield#constructor_3)(Page, Rectangle) | Constructor para Combobox Field. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Obtiene las acciones de anotación. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtiene o establece el estado actual de apariencia de la anotación. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Obtiene o establece el nombre alternativo del campo (un nombre de campo alternativo que se utilizará en lugar del nombre de campo real siempre que el campo se identifique en la interfaz de usuario). El nombre alternativo se utiliza como información sobre herramientas de campo en Adobe Acrobat . |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Obtiene o establece el índice de esta anotación en la página. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Obtiene el tipo de anotación. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtiene o establece las características del borde de la anotación.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtiene las características de la anotación. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtiene o establece el color de la anotación. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately) { get; set; } | Obtiene o establece la confirmación en el indicador de cambio de selección. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtiene o establece el texto de la anotación. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Obtiene o establece el número de subcampos en este campo. (Por ejemplo, número de elementos en el campo de botón de radio). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Obtiene o establece la apariencia predeterminada del campo. |
| [Editable](../../aspose.pdf.forms/comboboxfield/editable) { get; set; } | Obtiene o establece el estado editable del campo. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Obtiene o establece el indicador exportable del campo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Banderas de la anotación. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Obtiene el nombre calificado completo de la anotación. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Obtiene o establece la altura de la anotación. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Modo de resaltado de anotaciones. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para la generación de PDF) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Obtiene o establece un valor booleano que indica si este campo es un campo no terminal, es decir, un grupo de campos. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtiene o establece que un párrafo está en línea. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtiene o establece un valor booleano que obliga a generar este párrafo en una nueva página. El valor predeterminado es falso. (para la generación de PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el párrafo siguiente. El valor predeterminado es falso. (para la generación de PDF) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Propiedad para soporte de Generador. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Devuelve verdadero si el diccionario está sincronizado. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Obtiene el subcampo contenido en este campo por nombre del subcampo. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Obtiene o establece el nombre de asignación del campo que se utilizará al exportar datos de campo de formulario interactivo desde el documento. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Obtiene o establece la fecha y la hora en que se modificó recientemente la anotación. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect) { get; set; } | Obtiene o establece el indicador de selección múltiple. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Obtiene o establece el nombre de la anotación en la página. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | Acción que se realizará cuando se active la anotación. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options) { get; } | Obtiene la colección de opciones de elección. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Obtiene el índice de la página que contiene este campo. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Obtiene la anotación padre. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Obtiene o establece el nombre parcial del campo. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Obtiene o establece el estado de solo lectura del campo. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Obtiene o establece el campo rectángulo. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Obtiene o establece el estado requerido del campo. |
| virtual [Selected](../../aspose.pdf.forms/choicefield/selected) { get; set; } | Obtiene o establece el índice de la opción seleccionada. Esta propiedad permite cambiar la selección. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems) { get; set; } | Obtiene o establece una matriz de elementos seleccionados. Para la matriz de lista de selección múltiple, contiene más de un elemento. Para la lista de selección única, contiene un solo elemento. |
| [SpellCheck](../../aspose.pdf.forms/comboboxfield/spellcheck) { get; set; } | Obtiene o establece el estado de actividad del corrector ortográfico. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtiene el diccionario de apariencia de la anotación. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Objeto de sincronización. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Obtiene o establece el orden de tabulación del campo. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtiene o establece la alineación del texto para la anotación. |
| override [Value](../../aspose.pdf.forms/choicefield/value) { get; set; } | Obtiene o establece el valor del campo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtiene o establece el ancho de la anotación. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex más grande se colocará sobre el gráfico con ZIndex más pequeño. ZIndex puede ser negativo. El gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Acepta visitante. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string) | Agrega una nueva opción con el nombre especificado. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string, string) | Agrega una nueva opción con el valor de exportación y el nombre especificados. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Actualizar parámetros y apariencia, según la transformada de matriz. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clona esta instancia. Método virtual. Devuelve siempre null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Copia subcampos de este campo en una matriz a partir del índice especificado. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption)(string) | Borra la opción por su nombre. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Elimina este campo y coloca su valor directamente en la página. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Devuelve el enumerador de campos contenidos. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Devuelve el rectángulo de anotación teniendo en cuenta la rotación de página. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Vuelve a calcular todos los campos calculados en el formulario. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Establecer posición del campo. |

### Ver también

* class [ChoiceField](../choicefield)
* espacio de nombres [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
