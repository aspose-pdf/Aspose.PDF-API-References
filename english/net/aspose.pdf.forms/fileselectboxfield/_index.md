---
title: "FileSelectBoxField Class"
linktitle: "FileSelectBoxField"
articleTitle: "FileSelectBoxField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Forms.FileSelectBoxField class. Field for file select box element."
type: docs
weight: 130
url: "/net/aspose.pdf.forms/fileselectboxfield/"
keywords: "FileSelectBoxField, Aspose.Pdf.Forms, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FileSelectBoxField class

[Field](../field/) for file select box element.

```csharp
public sealed class FileSelectBoxField : TextBoxField
```

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Gets the annotation actions. *(Inherited from WidgetAnnotation)* |
| [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. *(Inherited from Annotation)* |
| [Alignment](../../aspose.pdf.annotations/annotation/alignment/) { get; set; } | Annotation alignment. This property is obsolete. Use HorizontalAligment instead. *(Inherited from Annotation)* |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Gets or sets alternate name of the field (An alternate field. *(Inherited from Field)* |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Gets or sets index of this anotation on the page. *(Inherited from Field)* |
| [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Gets type of annotation. *(Inherited from WidgetAnnotation)* |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. *(Inherited from Annotation)* |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border`. *(Inherited from Annotation)* |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. *(Inherited from Annotation)* |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. *(Inherited from Annotation)* |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. *(Inherited from Annotation)* |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Gets number of subfields in this field. (For example number of items in radio button field). *(Inherited from Field)* |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Gets or sets default appearance of the field. *(Inherited from WidgetAnnotation)* |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Gets or sets exportable flag of the field. *(Inherited from WidgetAnnotation)* |
| [FitIntoRectangle](../../aspose.pdf.forms/field/fitintorectangle/) { get; set; } | If true then font size will reduced to fit text to specified rectangle. *(Inherited from Field)* |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. *(Inherited from Annotation)* |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | Gets or sets flag which indicates is field divided into spaced positions. *(Inherited from TextBoxField)* |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. *(Inherited from Annotation)* |
| [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. *(Inherited from Annotation)* |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annotation highlighting mode. *(Inherited from WidgetAnnotation)* |
| [HorizontalAlignment](../../aspose.pdf.annotations/annotation/horizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Gets or sets boolean value which indicates is this field non-terminal field i.e. group of fields. *(Inherited from Field)* |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. *(Inherited from Field)* |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Returns true if dictionary is synchronized. *(Inherited from Field)* |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Gets subfield contained in this field by name of the subfield. *(Inherited from Field)* |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Gets or sets mapping name of the field that shall be used when exporting interactive form field data from the document. *(Inherited from Field)* |
| [MaxFontSize](../../aspose.pdf.forms/field/maxfontsize/) { get; set; } | Maximail font size which can be used for field contents. -1 to don't check size. *(Inherited from Field)* |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | Gets or sets maximum length of text in the field. *(Inherited from TextBoxField)* |
| [MinFontSize](../../aspose.pdf.forms/field/minfontsize/) { get; set; } | Minimal font size which can be used for field contents. -1 to don't check size. *(Inherited from Field)* |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. *(Inherited from Annotation)* |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | Gets or sets multiline flag of the field. If Multiline is true field can contain multiple lines of text. *(Inherited from TextBoxField)* |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. *(Inherited from Annotation)* |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | An action which shall be performed when the annotation is activated. *(Inherited from WidgetAnnotation)* |
| [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Gets index of page which contains this field. *(Inherited from Field)* |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Gets annotation parent. *(Inherited from WidgetAnnotation)* |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Gets or sets partial name of the field. *(Inherited from Field)* |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Gets or sets read only status of the field. *(Inherited from WidgetAnnotation)* |
| [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Gets or sets the field rectangle. *(Inherited from Field)* |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Gets or sets required status of the field. *(Inherited from WidgetAnnotation)* |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | Gets or sets scrollable flag of field. If true field can be scrolled. *(Inherited from TextBoxField)* |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | Gets or sets spellcheck flag for field. If true field shall be spell checked. *(Inherited from TextBoxField)* |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. *(Inherited from Annotation)* |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronization object. *(Inherited from Field)* |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Gets or sets tab order of the field. *(Inherited from Field)* |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | Gets or sets text vertical alignment for annotation. *(Inherited from TextBoxField)* |
| [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. *(Inherited from Annotation)* |
| [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. *(Inherited from Annotation)* |
| [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | Gets or sets value of the field. *(Inherited from TextBoxField)* |
| [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. *(Inherited from Annotation)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(*AnnotationSelector*) | Accepts visitor. *(Inherited from WidgetAnnotation)* |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(*string*) | Adds barcode 128 into the field. *(Inherited from TextBoxField)* |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(*Image*) | Adds image into the field resources and draws it. *(Inherited from TextBoxField)* |
| [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(*Matrix*) | Update parameters and appearance, according to the matrix transform. *(Inherited from Annotation)* |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(*Field[], int*) | Copies subfields of this field into array starting from specified index. *(Inherited from Field)* |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(*JavascriptAction*) | Executes a specified JavaScript action for the field. *(Inherited from Field)* |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(*Stream, ExportFieldsToJsonOptions*) | Exports the specified PDF form field to JSON format and writes the result to the provided stream. *(Inherited from WidgetAnnotation)* |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(*Stream, bool*) | Exports the content of the specified field into a JSON stream. Button field value are not exported. *(Inherited from Field)* |
| [Flatten](../../aspose.pdf.forms/field/flatten/) | Removes this field and place its value directly on the page. *(Inherited from Field)* |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/) | Returns name of "checked" state according to existing state names. *(Inherited from WidgetAnnotation)* |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/) | Returns enumerator of contained fields. *(Inherited from Field)* |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(*bool*) | Returns rectangle of annotation taking into consideration page rotation. *(Inherited from Annotation)* |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(*Stream*) | Imports data into the specified fields from a JSON stream, based on an exact match of the fields' full names. *(Inherited from Field)* |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(*Stream, string*) | Imports data into the specified field from a JSON stream, using the full name specified in the 'fieldFullNameInJSON' variable for matching. *(Inherited from Field)* |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/) | Recaculates all calculated fields on the form. *(Inherited from Field)* |
| [SetPosition](../../aspose.pdf.forms/field/setposition/)(*Point*) | Set position of the field. *(Inherited from Field)* |

### See Also

* class [TextBoxField](../textboxfield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)

