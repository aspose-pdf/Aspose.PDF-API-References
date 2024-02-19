---
title: Class DateField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.DateField class. Date field with calendar view
type: docs
weight: 3050
url: /net/aspose.pdf.forms/datefield/
---
## DateField class

Date field with calendar view.

```csharp
public class DateField : TextBoxField
```

## Constructors

| Name | Description |
| --- | --- |
| [DateField](datefield/#constructor)() | Initializes a new instance of the `DateField` |
| [DateField](datefield/#constructor_1)(Document) | Constructor which should be used with Generator. |
| [DateField](datefield/#constructor_2)(Document, Rectangle) | Initializes a new instance of the `DateField` |
| [DateField](datefield/#constructor_3)(Page, Rectangle) | Initializes a new instance of the `DateField` |

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
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Gets number of subfields in this field. (For example number of items in radio button field). |
| [DateFormat](../../aspose.pdf.forms/datefield/dateformat/) { get; set; } | Gets or sets the date format. |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Gets or sets default appearance of the field. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Gets or sets exportable flag of the field. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | Gets or sets flag which indicates is field divided into spaced positions. |
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
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | Gets or sets maximum length of text in the field. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | Gets or sets multiline flag of the field. If Multiline is true field can contain multiple lines of text. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | An action which shall be performed when the annotation is activated. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Gets index of page which contains this field. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Gets annotation parent. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Gets or sets partial name of the field. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Gets or sets read only status of the field. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Gets or sets the field rectangle. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Gets or sets required status of the field. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | Gets or sets scrollable flag of field. If true field can be scrolled. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | Gets or sets spellcheck flag for field. If true field shall be spell checked. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronization object. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Gets or sets tab order of the field. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | Gets or sets text vertical alignment for annotation. |
| [Value](../../aspose.pdf.forms/datefield/value/) { get; set; } | Gets or sets Date. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | Gets or sets value of the field. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepts visitor. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | Adds barcode 128 into the field. Field value will be changed onto the code and field become read only. |
| [AddImage](../../aspose.pdf.forms/datefield/addimage/#addimage)(Image) | Image adding denied for this field. (2 methods) |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clones this instance. Virtual method. Always return null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Copies subfields of this field into array starting from specified index. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Removes this field and place its value directly on the page. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returns name of "checked" state according to existing state names. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Returns enumerator of contained fields. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [Init](../../aspose.pdf.forms/datefield/init/)(Page) | Initializes the JS Action. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Recaculates all calculated fields on the form. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Set position of the field. |

## Examples

DateField dateField = new DateField(page, rect); doc.Form.Add(dateField); dateField.Init(page);

### See Also

* class [TextBoxField](../textboxfield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


