---
title: Class ChoiceField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ChoiceField class. Represents base class for choice fields
type: docs
weight: 3400
url: /net/aspose.pdf.forms/choicefield/
---
## ChoiceField class

Represents base class for choice fields.

```csharp
public abstract class ChoiceField : Field
```

## Constructors

| Name | Description |
| --- | --- |
| [ChoiceField](choicefield/#constructor)(Document) | Creates choice field (for Generator) |
| [ChoiceField](choicefield/#constructor_1)(Document, Rectangle) | Constructor for ChoiceField. |
| [ChoiceField](choicefield/#constructor_2)(Page, Rectangle) | Constructor for ChoiceField. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Gets the annotation actions. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Gets or sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Gets or sets index of this anotation on the page. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Gets or sets commit on selection change flag. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Gets number of subfields in this field. (For example number of items in radio button field). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Gets or sets default appearance of the field. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Gets or sets exportable flag of the field. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annotation highlighting mode. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Gets or sets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Returns true if dictionary is synchronized. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Gets subfield contained in this field by name of the subfield. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Gets or sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Gets or sets multiselection flag. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | An action which shall be performed when the annotation is activated. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Gets collection of choice options. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Gets index of page which contains this field. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Gets annotation parent. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Gets or sets partial name of the field. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Gets or sets read only status of the field. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Gets or sets the field rectangle. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Gets or sets required status of the field. |
| virtual [Selected](../../aspose.pdf.forms/choicefield/selected/) { get; set; } | Gets or sets index of selected option. This property allows to change selection. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | Gets or sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronization object. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Gets or sets tab order of the field. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Gets or sets value of the field. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepts visitor. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/#addoption)(string) | Adds new option with specified name. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/#addoption_1)(string, string) | Adds new option with specified export value and name. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clones this instance. Virtual method. Always return null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Copies subfields of this field into array starting from specified index. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Deletes option by its name. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Executes a specified JavaScript action for the field. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Removes this field and place its value directly on the page. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returns name of "checked" state according to existing state names. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Returns enumerator of contained fields. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Recaculates all calculated fields on the form. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Set position of the field. |

### See Also

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


