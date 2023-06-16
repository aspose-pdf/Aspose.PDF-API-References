---
title: RadioButtonField
second_title: Aspose.PDF for .NET API Reference
description: Class representing radio button field.
type: docs
weight: 3200
url: /net/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class

Class representing radio button field.

```csharp
public sealed class RadioButtonField : ChoiceField
```

## Constructors

| Name | Description |
| --- | --- |
| [RadioButtonField](radiobuttonfield#constructor)(Document) | Constructor for RadioButtonField. |
| [RadioButtonField](radiobuttonfield#constructor_1)(Page) | Constructor for RadiouttonField |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Gets the annotation actions. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Gets or sets current annotation appearance state. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Gets or sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Gets or sets index of this anotation on the page. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Gets or sets annotation border characteristics. [`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Gets or sets annotation color. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately) { get; set; } | Gets or sets commit on selection change flag. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Gets or sets annotation text. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Gets number of subfields in this field. (For example number of items in radio button field). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Gets or sets default appearance of the field. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Gets or sets exportable flag of the field. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Gets or sets height of the annotation. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Annotation highlighting mode. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Gets or sets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Returns true if dictionary is synchronized. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Gets subfield contained in this field by name of the subfield. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Gets or sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect) { get; set; } | Gets or sets multiselection flag. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Gets or sets annotation name on the page. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | An action which shall be performed when the annotation is activated. |
| override [Options](../../aspose.pdf.forms/radiobuttonfield/options) { get; } | Gets collection of options of the radio button. |
| override [PageIndex](../../aspose.pdf.forms/radiobuttonfield/pageindex) { get; } | Gets index of page which contains this RadioButton field. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Gets annotation parent. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Gets or sets partial name of the field. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Gets or sets read only status of the field. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Gets or sets the field rectangle. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Gets or sets required status of the field. |
| override [Selected](../../aspose.pdf.forms/radiobuttonfield/selected) { get; set; } | Gets or sets index of selected item. Numbering of items is started from 1. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems) { get; set; } | Gets or sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Gets appearance dictionary of annotation. |
| [Style](../../aspose.pdf.forms/radiobuttonfield/style) { get; set; } | Style of field box. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Synchronization object. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Gets or sets tab order of the field. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Gets or sets text alignment for annotation. |
| override [Value](../../aspose.pdf.forms/radiobuttonfield/value) { get; set; } | Gets or sets value of field. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Gets or sets a vertical alignment of paragraph |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Gets or sets width of the annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Accepts visitor. |
| [Add](../../aspose.pdf.forms/radiobuttonfield/add)(RadioButtonOptionField) | Adds new option field to RadioButton field |
| override [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption#addoption)(string) | Add option to radion button. |
| [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption#addoption_1)(string, Rectangle) | Add to radio button option with specifed rectangle. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string, string) | Adds new option with specified export value and name. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clones this instance. Virtual method. Always return null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Copies subfields of this field into array starting from specified index. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption)(string) | Deletes option by its name. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Removes this field and place its value directly on the page. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Returns enumerator of contained fields. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Recaculates all calculated fields on the form. |
| override [SetPosition](../../aspose.pdf.forms/radiobuttonfield/setposition)(Point) | Move all subitems of radio button to specified positins on the page. |

### See Also

* class [ChoiceField](../choicefield)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
