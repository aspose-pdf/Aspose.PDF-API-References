---
title: "Field Class"
linktitle: "Field"
articleTitle: "Field"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Forms.Field class. Base class for acro form fields."
type: docs
weight: 120
url: "/net/aspose.pdf.forms/field/"
keywords: "Field, Aspose.Pdf.Forms, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Field class

Base class for acro form fields.

```csharp
public class Field : WidgetAnnotation, ICollection<WidgetAnnotation>
```

## Constructors

| Name | Description |
| --- | --- |
| [Field](./field/)(Document) | Creates field for use in Generator. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Gets the annotation actions. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| [AlternateName](./alternatename/) { get; set; } | Gets or sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [AnnotationIndex](./annotationindex/) { get; set; } | Gets or sets index of this anotation on the page. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border` |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [Count](./count/) { get; } | Gets number of subfields in this field. (For example number of items in radio button field). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Gets or sets default appearance of the field. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Gets or sets exportable flag of the field. |
| static [FitIntoRectangle](./fitintorectangle/) { get; set; } | If true then font size will reduced to fit text to specified rectangle. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annotation highlighting mode. |
| [IsGroup](./isgroup/) { get; } | Gets or sets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [IsSharedField](./issharedfield/) { get; set; } | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [IsSynchronized](./issynchronized/) { get; } | Returns true if dictionary is synchronized. |
| [Item](./item/) { get; } | Gets subfield contained in this field by name of the subfield. (2 indexers) |
| [MappingName](./mappingname/) { get; set; } | Gets or sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| static [MaxFontSize](./maxfontsize/) { get; set; } | Maximail font size which can be used for field contents. -1 to don't check size. |
| static [MinFontSize](./minfontsize/) { get; set; } | Minimal font size which can be used for field contents. -1 to don't check size. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | An action which shall be performed when the annotation is activated. |
| override [PageIndex](./pageindex/) { get; } | Gets index of page which contains this field. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Gets annotation parent. |
| [PartialName](./partialname/) { get; set; } | Gets or sets partial name of the field. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Gets or sets read only status of the field. |
| override [Rect](./rect/) { get; set; } | Gets or sets the field rectangle. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Gets or sets required status of the field. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. |
| [SyncRoot](./syncroot/) { get; } | Synchronization object. |
| [TabOrder](./taborder/) { get; set; } | Gets or sets tab order of the field. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| static [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [Value](./value/) { get; set; } | Gets or sets value of the field. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepts visitor. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| [CopyTo](./copyto/)(WidgetAnnotation[], int) | Copies subfields of this field into array starting from specified index. |
| [ExecuteFieldJavaScript](./executefieldjavascript/)(JavascriptAction) | Executes a specified JavaScript action for the field. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exports the specified PDF form field to JSON format and writes the result to the provided stream. |
| [ExportValueToJson](./exportvaluetojson/)(Stream, bool) | Exports the content of the specified field into a JSON stream. Button field value are not exported. |
| override [Flatten](./flatten/)() | Removes this field and place its value directly on the page. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returns name of "checked" state according to existing state names. |
| [GetEnumerator](./getenumerator/)() | Returns enumerator of contained fields. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [ImportValueFromJson](./importvaluefromjson/)(Stream) | Imports data into the specified fields from a JSON stream, based on an exact match of the fields' full names. |
| [ImportValueFromJson](./importvaluefromjson/)(Stream, string) | Imports data into the specified field from a JSON stream, using the full name specified in the 'fieldFullNameInJSON' variable for matching. |
| [Recalculate](./recalculate/)() | Recaculates all calculated fields on the form. |
| virtual [SetPosition](./setposition/)(Point) | Set position of the field. |

### See Also

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)

