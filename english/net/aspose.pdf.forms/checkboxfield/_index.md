---
title: "CheckboxField Class"
linktitle: "CheckboxField"
articleTitle: "CheckboxField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Forms.CheckboxField class. Class representing checkbox field"
type: docs
weight: 50
url: "/net/aspose.pdf.forms/checkboxfield/"
keywords: "CheckboxField, Aspose.Pdf.Forms, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CheckboxField class

Class representing checkbox field

```csharp
public class CheckboxField : Field
```

## Constructors

| Name | Description |
| --- | --- |
| [CheckboxField](./checkboxfield/#constructor) | Create instance of CheckboxField. |
| [CheckboxField](./checkboxfield/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Constructor to use with Generator. |
| [CheckboxField](./checkboxfield/#constructor_2)(*[Page](../../aspose.pdf/page/), [Rectangle](../../aspose.pdf.drawing/rectangle/)*) | Constructor for CheckboxField class. |
| [CheckboxField](./checkboxfield/#constructor_3)(*[Document](../../aspose.pdf/document/), [Rectangle](../../aspose.pdf.drawing/rectangle/)*) | Constructor for CheckboxField class. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Gets the annotation actions. *(Inherited from WidgetAnnotation)* |
| [ActiveState](./activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| [Alignment](../../aspose.pdf.annotations/annotation/alignment/) { get; set; } | Annotation alignment. This property is obsolete. Use HorizontalAligment instead. *(Inherited from Annotation)* |
| [AllowedStates](./allowedstates/) { get; } | Returns list of allowed states. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Gets or sets alternate name of the field (An alternate field. *(Inherited from Field)* |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Gets or sets index of this anotation on the page. *(Inherited from Field)* |
| [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Gets type of annotation. *(Inherited from WidgetAnnotation)* |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. *(Inherited from Annotation)* |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border`. *(Inherited from Annotation)* |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. *(Inherited from Annotation)* |
| [Checked](./checked/) { get; set; } | Gets or sets state of check box. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. *(Inherited from Annotation)* |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. *(Inherited from Annotation)* |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Gets number of subfields in this field. (For example number of items in radio button field). *(Inherited from Field)* |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Gets or sets default appearance of the field. *(Inherited from WidgetAnnotation)* |
| [ExportValue](./exportvalue/) { get; set; } | Gets or sets export value of CheckBox field. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Gets or sets exportable flag of the field. *(Inherited from WidgetAnnotation)* |
| [FitIntoRectangle](../../aspose.pdf.forms/field/fitintorectangle/) { get; set; } | If true then font size will reduced to fit text to specified rectangle. *(Inherited from Field)* |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. *(Inherited from Annotation)* |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. *(Inherited from Annotation)* |
| [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. *(Inherited from Annotation)* |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Annotation highlighting mode. *(Inherited from WidgetAnnotation)* |
| [HorizontalAlignment](../../aspose.pdf.annotations/annotation/horizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [InnerRect](../../aspose.pdf.annotations/annotation/innerrect/) { get; } | Returns internal rectnagle of annotation, i.e. rectangle recalculated according to RD entry of annotation. *(Inherited from Annotation)* |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Gets or sets boolean value which indicates is this field non-terminal field i.e. group of fields. *(Inherited from Field)* |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. *(Inherited from Field)* |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Returns true if dictionary is synchronized. *(Inherited from Field)* |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | *(Inherited from Field)* |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Gets or sets mapping name of the field that shall be used when exporting interactive form field data from the document. *(Inherited from Field)* |
| [MaxFontSize](../../aspose.pdf.forms/field/maxfontsize/) { get; set; } | Maximail font size which can be used for field contents. -1 to don't check size. *(Inherited from Field)* |
| [MinFontSize](../../aspose.pdf.forms/field/minfontsize/) { get; set; } | Minimal font size which can be used for field contents. -1 to don't check size. *(Inherited from Field)* |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. *(Inherited from Annotation)* |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. *(Inherited from Annotation)* |
| [NormalAppearance](../../aspose.pdf.annotations/annotation/normalappearance/) { get; } | Gets normal appearance. *(Inherited from Annotation)* |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | An action which shall be performed when the annotation is activated. *(Inherited from WidgetAnnotation)* |
| [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Gets index of page which contains this field. *(Inherited from Field)* |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Gets annotation parent. *(Inherited from WidgetAnnotation)* |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Gets or sets partial name of the field. *(Inherited from Field)* |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Gets or sets read only status of the field. *(Inherited from WidgetAnnotation)* |
| [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Gets or sets the field rectangle. *(Inherited from Field)* |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Gets or sets required status of the field. *(Inherited from WidgetAnnotation)* |
| [RotatedRect](../../aspose.pdf.annotations/annotation/rotatedrect/) { get; } | Gets rotated rectangle. *(Inherited from Annotation)* |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. *(Inherited from Annotation)* |
| [Style](./style/) { get; set; } | Gets or sets style of check box. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Synchronization object. *(Inherited from Field)* |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Gets or sets tab order of the field. *(Inherited from Field)* |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. *(Inherited from Annotation)* |
| [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. *(Inherited from Annotation)* |
| [Value](./value/) { get; set; } | Gets or sets value of check box field. |
| [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. *(Inherited from Annotation)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(*AnnotationSelector*) | Accepts visitor. *(Inherited from WidgetAnnotation)* |
| [AddOption](./addoption/)(*string*) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. |
| [AddOption](./addoption/)(*string, Rectangle*) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. |
| [AddOption](./addoption/)(*string, int, Rectangle*) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. |
| [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(*Matrix*) | Update parameters and appearance, according to the matrix transform. *(Inherited from Annotation)* |
| [Clone](./clone/) | Clone the checkbox. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(*Field[], int*) | Copies subfields of this field into array starting from specified index. *(Inherited from Field)* |
| [CreateExtGStateWithOpacity](../../aspose.pdf.annotations/annotation/createextgstatewithopacity/)(*XForm*) | *(Inherited from Annotation)* |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(*JavascriptAction*) | Executes a specified JavaScript action for the field. *(Inherited from Field)* |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(*Stream, ExportFieldsToJsonOptions*) | Exports the specified PDF form field to JSON format and writes the result to the provided stream. *(Inherited from WidgetAnnotation)* |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(*Stream, bool*) | Exports the content of the specified field into a JSON stream. Button field value are not exported. *(Inherited from Field)* |
| [Flatten](../../aspose.pdf.forms/field/flatten/) | Removes this field and place its value directly on the page. *(Inherited from Field)* |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/) | Returns name of "checked" state according to existing state names. *(Inherited from WidgetAnnotation)* |
| [GetConformXFAValue](../../aspose.pdf.forms/field/getconformxfavalue/)(*string*) | Returns value correctly encoded for placing into XFA dataset. *(Inherited from Field)* |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/) | Returns enumerator of contained fields. *(Inherited from Field)* |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(*bool*) | Returns rectangle of annotation taking into consideration page rotation. *(Inherited from Annotation)* |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(*Stream*) | Imports data into the specified fields from a JSON stream, based on an exact match of the fields' full names. *(Inherited from Field)* |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(*Stream, string*) | Imports data into the specified field from a JSON stream, using the full name specified in the 'fieldFullNameInJSON' variable for matching. *(Inherited from Field)* |
| [Initialize](../../aspose.pdf.annotations/annotation/initialize/)(*Page, Rectangle*) | Initialize the annotation. *(Inherited from Annotation)* |
| [IsEqualTo](../../aspose.pdf.forms/field/isequalto/)(*string*) | Operator for comparision field value with given value. *(Inherited from Field)* |
| [ReadXfdfAttributes](../../aspose.pdf.annotations/annotation/readxfdfattributes/)(*XmlReader*) | When overridden in a derived class, import annotation attributes from XFDF. *(Inherited from Annotation)* |
| [ReadXfdfElements](../../aspose.pdf.annotations/annotation/readxfdfelements/)(*Dictionary<string, string>*) | When overridden in a derived class, import annotation elements from XFDF. *(Inherited from Annotation)* |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/) | Recaculates all calculated fields on the form. *(Inherited from Field)* |
| [SetPosition](../../aspose.pdf.forms/field/setposition/)(*Point*) | Set position of the field. *(Inherited from Field)* |
| [ToImage](../../aspose.pdf.annotations/annotation/toimage/)(*ImageFormat*) | Converts annotation to image stream. *(Inherited from Annotation)* |
| [WriteXfdfAttributes](../../aspose.pdf.annotations/annotation/writexfdfattributes/)(*XmlWriter*) | When overridden in a derived class, exports annotation attributes into XFDF. *(Inherited from Annotation)* |
| [WriteXfdfElements](../../aspose.pdf.annotations/annotation/writexfdfelements/)(*XmlWriter*) | When overridden in a derived class, exports annotation elements into XFDF. *(Inherited from Annotation)* |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultFontKey](../../aspose.pdf.annotations/annotation/defaultfontkey/) | *(Inherited from Annotation)* |
| const [DefaultFontName](../../aspose.pdf.annotations/annotation/defaultfontname/) | *(Inherited from Annotation)* |
| const [DefaultFontSize](../../aspose.pdf.annotations/annotation/defaultfontsize/) | *(Inherited from Annotation)* |
| [_states](../../aspose.pdf.annotations/annotation/_states/) | *(Inherited from Annotation)* |
| [ff](../../aspose.pdf.annotations/widgetannotation/ff/) | *(Inherited from WidgetAnnotation)* |

### See Also

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)

