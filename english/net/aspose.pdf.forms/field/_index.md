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
public class Field : WidgetAnnotation, IEnumerable
```

## Constructors

| Name | Description |
| --- | --- |
| [Field](./field/#constructor)(*[Document](../../aspose.pdf/document/)*) | Creates field for use in Generator. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Gets the annotation actions. *(Inherited from WidgetAnnotation)* |
| [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. *(Inherited from Annotation)* |
| [Alignment](../../aspose.pdf.annotations/annotation/alignment/) { get; set; } | Annotation alignment. This property is obsolete. Use HorizontalAligment instead. *(Inherited from Annotation)* |
| [AlternateName](./alternatename/) { get; set; } | Gets or sets alternate name of the field (An alternate field. |
| [AnnotationIndex](./annotationindex/) { get; set; } | Gets or sets index of this anotation on the page. |
| [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Gets type of annotation. *(Inherited from WidgetAnnotation)* |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. *(Inherited from Annotation)* |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border`. *(Inherited from Annotation)* |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. *(Inherited from Annotation)* |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. *(Inherited from Annotation)* |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. *(Inherited from Annotation)* |
| [Count](./count/) { get; } | Gets number of subfields in this field. (For example number of items in radio button field). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Gets or sets default appearance of the field. *(Inherited from WidgetAnnotation)* |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Gets or sets exportable flag of the field. *(Inherited from WidgetAnnotation)* |
| [FitIntoRectangle](./fitintorectangle/) { get; set; } | If true then font size will reduced to fit text to specified rectangle. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. *(Inherited from Annotation)* |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. *(Inherited from Annotation)* |
| [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. *(Inherited from Annotation)* |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annotation highlighting mode. *(Inherited from WidgetAnnotation)* |
| [HorizontalAlignment](../../aspose.pdf.annotations/annotation/horizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [IsGroup](./isgroup/) { get; } | Gets or sets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [IsSharedField](./issharedfield/) { get; set; } | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [IsSynchronized](./issynchronized/) { get; } | Returns true if dictionary is synchronized. |
| [Item](./item/) { get; } | Gets subfield contained in this field by name of the subfield. |
| [Item](./item/) { get; } | Gets subfield contained in this field by index. |
| [MappingName](./mappingname/) { get; set; } | Gets or sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [MaxFontSize](./maxfontsize/) { get; set; } | Maximail font size which can be used for field contents. -1 to don't check size. |
| [MinFontSize](./minfontsize/) { get; set; } | Minimal font size which can be used for field contents. -1 to don't check size. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. *(Inherited from Annotation)* |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. *(Inherited from Annotation)* |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | An action which shall be performed when the annotation is activated. *(Inherited from WidgetAnnotation)* |
| [PageIndex](./pageindex/) { get; } | Gets index of page which contains this field. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Gets annotation parent. *(Inherited from WidgetAnnotation)* |
| [PartialName](./partialname/) { get; set; } | Gets or sets partial name of the field. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Gets or sets read only status of the field. *(Inherited from WidgetAnnotation)* |
| [Rect](./rect/) { get; set; } | Gets or sets the field rectangle. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Gets or sets required status of the field. *(Inherited from WidgetAnnotation)* |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. *(Inherited from Annotation)* |
| [SyncRoot](./syncroot/) { get; } | Synchronization object. |
| [TabOrder](./taborder/) { get; set; } | Gets or sets tab order of the field. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. *(Inherited from Annotation)* |
| [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. *(Inherited from Annotation)* |
| [Value](./value/) { get; set; } | Gets or sets value of the field. |
| [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. *(Inherited from Annotation)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(*AnnotationSelector*) | Accepts visitor. *(Inherited from WidgetAnnotation)* |
| [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(*Matrix*) | Update parameters and appearance, according to the matrix transform. *(Inherited from Annotation)* |
| [CopyTo](./copyto/)(*Field[], int*) | Copies subfields of this field into array starting from specified index. |
| [CopyTo](./copyto/)(*WidgetAnnotation[], int*) | Copies subfields of this field into array starting from specified index. |
| [ExecuteFieldJavaScript](./executefieldjavascript/)(*JavascriptAction*) | Executes a specified JavaScript action for the field. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(*Stream, ExportFieldsToJsonOptions*) | Exports the specified PDF form field to JSON format and writes the result to the provided stream. *(Inherited from WidgetAnnotation)* |
| [ExportValueToJson](./exportvaluetojson/)(*Stream, bool*) | Exports the content of the specified field into a JSON stream. Button field value are not exported. |
| [Flatten](./flatten/) | Removes this field and place its value directly on the page. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/) | Returns name of "checked" state according to existing state names. *(Inherited from WidgetAnnotation)* |
| [GetEnumerator](./getenumerator/) | Returns enumerator of contained fields. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(*bool*) | Returns rectangle of annotation taking into consideration page rotation. *(Inherited from Annotation)* |
| [ImportValueFromJson](./importvaluefromjson/)(*Stream*) | Imports data into the specified fields from a JSON stream, based on an exact match of the fields' full names. |
| [ImportValueFromJson](./importvaluefromjson/)(*Stream, string*) | Imports data into the specified field from a JSON stream, using the full name specified in the 'fieldFullNameInJSON' variable for matching. |
| [Recalculate](./recalculate/) | Recaculates all calculated fields on the form. |
| [SetPosition](./setposition/)(*Point*) | Set position of the field. |

### See Also

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)

