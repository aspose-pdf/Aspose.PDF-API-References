---
title: Aspose::Pdf::Forms::Field class
linktitle: Field
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Field class. Base class for acro form fields in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.forms/field/
---
## Field class


Base class for acro form fields.

```cpp
class Field : public Aspose::Pdf::Annotations::WidgetAnnotation,
              public System::Collections::Generic::ICollection<System::SharedPtr<Annotations::WidgetAnnotation>>
```

## Methods

| Method | Description |
| --- | --- |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Field\>\>, int32_t) | Copies subfields of this field into array starting from specified index. |
| [CopyToWidgetArray](./copytowidgetarray/)(System::ArrayPtr\<System::SharedPtr\<Annotations::WidgetAnnotation\>\>, int32_t) | Copies subfields of this field into array starting from specified index. |
| [ExecuteFieldJavaScript](./executefieldjavascript/)(System::SharedPtr\<Annotations::JavascriptAction\>) | Executes a specified JavaScript action for the field. |
| [Field](./field/)(System::SharedPtr\<Document\>) | Creates field for use in Generator. |
| [Flatten](./flatten/)() override | Removes this field and place its value directly on the page. |
| [get_AlternateName](./get_alternatename/)() | Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [get_AnnotationIndex](./get_annotationindex/)() | Gets index of this anotation on the page. |
| [get_Count](./get_count/)() const override | Gets number of subfields in this field. (For example number of items in radio button field). |
| static [get_FitIntoRectangle](./get_fitintorectangle/)() | If true then font size will reduced to fit text to specified rectangle. |
| [get_IsGroup](./get_isgroup/)() const | Gets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [get_IsSharedField](./get_issharedfield/)() const | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true if dictionary is synchronized. |
| [get_MappingName](./get_mappingname/)() | Gets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| static [get_MaxFontSize](./get_maxfontsize/)() | Maximail font size which can be used for field contents. -1 to don't check size. |
| static [get_MinFontSize](./get_minfontsize/)() | Minimal font size which can be used for field contents. -1 to don't check size. |
| [get_PageIndex](./get_pageindex/)() override | Gets index of page which contains this field. |
| [get_PartialName](./get_partialname/)() | Gets partial name of the field. |
| [get_Rect](./get_rect/)() override | Gets the field rectangle. |
| [get_SyncRoot](./get_syncroot/)() const | Synchronization object. |
| [get_TabOrder](./get_taborder/)() | Gets tab order of the field. |
| virtual [get_Value](./get_value/)() | Gets value of the field. |
| [GetEnumerator](./getenumerator/)() override | Returns enumerator of contained fields. |
| [idx_get](./idx_get/)(System::String) | Gets subfield contained in this field by name of the subfield. |
| [idx_get](./idx_get/)(int32_t) | Gets subfield contained in this field by index. |
| [Recalculate](./recalculate/)() | Recaculates all calculated fields on the form. |
| [set_AlternateName](./set_alternatename/)(System::String) | Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [set_AnnotationIndex](./set_annotationindex/)(int32_t) | Sets index of this anotation on the page. |
| static [set_FitIntoRectangle](./set_fitintorectangle/)(bool) | If true then font size will reduced to fit text to specified rectangle. |
| [set_IsSharedField](./set_issharedfield/)(bool) | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [set_MappingName](./set_mappingname/)(System::String) | Sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| static [set_MaxFontSize](./set_maxfontsize/)(double) | Maximail font size which can be used for field contents. -1 to don't check size. |
| static [set_MinFontSize](./set_minfontsize/)(double) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [set_PartialName](./set_partialname/)(System::String) | Sets partial name of the field. |
| [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) override | Sets the field rectangle. |
| [set_TabOrder](./set_taborder/)(int32_t) | Sets tab order of the field. |
| virtual [set_Value](./set_value/)(System::String) | Sets value of the field. |
| virtual [SetPosition](./setposition/)(System::SharedPtr\<Point\>) | Set position of the field. |
## See Also

* Class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
