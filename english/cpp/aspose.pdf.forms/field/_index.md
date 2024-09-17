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
              public System::Collections::Generic::ICollection<System::SharedPtr<Aspose::Pdf::Annotations::WidgetAnnotation>>
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor. |
| [BaseParagraph](../../aspose.pdf/baseparagraph/baseparagraph/)() |  |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(System::SharedPtr\<Matrix\>) | Update parameters and appearance, according to the matrix transform. |
| [Clone](../../aspose.pdf/baseparagraph/clone/)() override | Clones this instance. Virtual method. Always return null. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Field\>\>, int32_t) | Copies subfields of this field into array starting from specified index. |
| [CopyToWidgetArray](./copytowidgetarray/)(System::ArrayPtr\<System::SharedPtr\<Aspose::Pdf::Annotations::WidgetAnnotation\>\>, int32_t) | Copies subfields of this field into array starting from specified index. |
| [ExecuteFieldJavaScript](./executefieldjavascript/)(System::SharedPtr\<Aspose::Pdf::Annotations::JavascriptAction\>) | Executes a specified JavaScript action for the field. |
| [Field](./field/)(System::SharedPtr\<Document\>) | Creates field for use in Generator. |
| [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [get_Actions](../../aspose.pdf.annotations/widgetannotation/get_actions/)() const | Gets the annotation actions. |
| [get_Actions](../../aspose.pdf.annotations/annotation/get_actions/)() | Gets list of annotatation actions. |
| virtual [get_ActiveState](../../aspose.pdf.annotations/annotation/get_activestate/)() | Gets current annotation appearance state. |
| [get_Alignment](../../aspose.pdf.annotations/annotation/get_alignment/)() | [Annotation](../../aspose.pdf.annotations/annotation/) alignment. This property is obsolete. Use HorizontalAligment instead. |
| [get_AlternateName](./get_alternatename/)() | Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [get_AnnotationIndex](./get_annotationindex/)() | Gets index of this anotation on the page. |
| [get_AnnotationType](../../aspose.pdf.annotations/widgetannotation/get_annotationtype/)() override | Gets type of annotation. |
| [get_Appearance](../../aspose.pdf.annotations/annotation/get_appearance/)() | Gets appearance dictionary of the annotation. |
| [get_Border](../../aspose.pdf.annotations/annotation/get_border/)() const | Gets annotation border characteristics. [Border](../../aspose.pdf.annotations/border/) |
| [get_Characteristics](../../aspose.pdf.annotations/annotation/get_characteristics/)() | Gets annotation characteristics. |
| [get_Color](../../aspose.pdf.annotations/annotation/get_color/)() | Gets annotation color. |
| [get_Contents](../../aspose.pdf.annotations/annotation/get_contents/)() | Gets annotation text. |
| [get_Count](./get_count/)() const override | Gets number of subfields in this field. (For example number of items in radio button field). |
| [get_DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/get_defaultappearance/)() | Gets default appearance of the field. |
| [get_Exportable](../../aspose.pdf.annotations/widgetannotation/get_exportable/)() | Gets exportable flag of the field. |
| static [get_FitIntoRectangle](./get_fitintorectangle/)() | If true then font size will reduced to fit text to specified rectangle. |
| [get_Flags](../../aspose.pdf.annotations/annotation/get_flags/)() | Flags of the annotation. |
| [get_FullName](../../aspose.pdf.annotations/annotation/get_fullname/)() | Gets full qualified name of the annotation. |
| virtual [get_Height](../../aspose.pdf.annotations/annotation/get_height/)() | Gets height of the annotation. |
| [get_Highlighting](../../aspose.pdf.annotations/widgetannotation/get_highlighting/)() | [Annotation](../../aspose.pdf.annotations/annotation/) highlighting mode. |
| [get_HorizontalAlignment](../../aspose.pdf.annotations/annotation/get_horizontalalignment/)() override | Gets text alignment for annotation. |
| virtual [get_Hyperlink](../../aspose.pdf/baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsGroup](./get_isgroup/)() const | Gets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [get_IsInLineParagraph](../../aspose.pdf/baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../../aspose.pdf/baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../../aspose.pdf/baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_IsSharedField](./get_issharedfield/)() const | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true if dictionary is synchronized. |
| [get_MappingName](./get_mappingname/)() | Gets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [get_Margin](../../aspose.pdf/baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| static [get_MaxFontSize](./get_maxfontsize/)() | Maximail font size which can be used for field contents. -1 to don't check size. |
| static [get_MinFontSize](./get_minfontsize/)() | Minimal font size which can be used for field contents. -1 to don't check size. |
| [get_Modified](../../aspose.pdf.annotations/annotation/get_modified/)() | Gets date and time when annotation was recently modified. |
| [get_Name](../../aspose.pdf.annotations/annotation/get_name/)() | Gets annotation name on the page. |
| [get_OnActivated](../../aspose.pdf.annotations/widgetannotation/get_onactivated/)() | An action which shall be performed when the annotation is activated. |
| [get_PageIndex](./get_pageindex/)() override | Gets index of page which contains this field. |
| [get_Parent](../../aspose.pdf.annotations/widgetannotation/get_parent/)() | Gets annotation parent. |
| [get_PartialName](./get_partialname/)() | Gets partial name of the field. |
| [get_ReadOnly](../../aspose.pdf.annotations/widgetannotation/get_readonly/)() | Gets read only status of the field. |
| [get_Rect](./get_rect/)() override | Gets the field rectangle. |
| [get_Required](../../aspose.pdf.annotations/widgetannotation/get_required/)() | Gets required status of the field. |
| [get_States](../../aspose.pdf.annotations/annotation/get_states/)() | Gets appearance dictionary of annotation. |
| [get_SyncRoot](./get_syncroot/)() const | Synchronization object. |
| [get_TabOrder](./get_taborder/)() | Gets tab order of the field. |
| [get_TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/get_texthorizontalalignment/)() | Gets text alignment for annotation. |
| static [get_UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/get_updateappearanceonconvert/)() | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [get_UseFontSubset](../../aspose.pdf.annotations/annotation/get_usefontsubset/)() | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [get_Value](./get_value/)() | Gets value of the field. |
| virtual [get_VerticalAlignment](../../aspose.pdf/baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| virtual [get_Width](../../aspose.pdf.annotations/annotation/get_width/)() | Gets width of the annotation. |
| [get_ZIndex](../../aspose.pdf/baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returns name of "checked" state according to existing state names. |
| [GetEnumerator](./getenumerator/)() override | Returns enumerator of contained fields. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [idx_get](./idx_get/)(System::String) | Gets subfield contained in this field by name of the subfield. |
| [idx_get](./idx_get/)(int32_t) | Gets subfield contained in this field by index. |
| [Recalculate](./recalculate/)() | Recaculates all calculated fields on the form. |
| virtual [set_ActiveState](../../aspose.pdf.annotations/annotation/set_activestate/)(System::String) | Sets current annotation appearance state. |
| [set_Alignment](../../aspose.pdf.annotations/annotation/set_alignment/)(TextAlignment) | [Annotation](../../aspose.pdf.annotations/annotation/) alignment. This property is obsolete. Use HorizontalAligment instead. |
| [set_AlternateName](./set_alternatename/)(System::String) | Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [set_AnnotationIndex](./set_annotationindex/)(int32_t) | Sets index of this anotation on the page. |
| [set_Border](../../aspose.pdf.annotations/annotation/set_border/)(System::SharedPtr\<Aspose::Pdf::Annotations::Border\>) | Sets annotation border characteristics. [Border](../../aspose.pdf.annotations/border/) |
| [set_Color](../../aspose.pdf.annotations/annotation/set_color/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets annotation color. |
| [set_Contents](../../aspose.pdf.annotations/annotation/set_contents/)(System::String) | Sets annotation text. |
| [set_DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/set_defaultappearance/)(System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>) | Sets default appearance of the field. |
| [set_Exportable](../../aspose.pdf.annotations/widgetannotation/set_exportable/)(bool) | Sets exportable flag of the field. |
| static [set_FitIntoRectangle](./set_fitintorectangle/)(bool) | If true then font size will reduced to fit text to specified rectangle. |
| [set_Flags](../../aspose.pdf.annotations/annotation/set_flags/)(AnnotationFlags) | Flags of the annotation. |
| virtual [set_Height](../../aspose.pdf.annotations/annotation/set_height/)(double) | Sets height of the annotation. |
| [set_Highlighting](../../aspose.pdf.annotations/widgetannotation/set_highlighting/)(HighlightingMode) | [Annotation](../../aspose.pdf.annotations/annotation/) highlighting mode. |
| [set_HorizontalAlignment](../../aspose.pdf.annotations/annotation/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Sets text alignment for annotation. |
| virtual [set_Hyperlink](../../aspose.pdf/baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../../aspose.pdf/baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../../aspose.pdf/baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../../aspose.pdf/baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_IsSharedField](./set_issharedfield/)(bool) | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [set_MappingName](./set_mappingname/)(System::String) | Sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [set_Margin](../../aspose.pdf/baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| static [set_MaxFontSize](./set_maxfontsize/)(double) | Maximail font size which can be used for field contents. -1 to don't check size. |
| static [set_MinFontSize](./set_minfontsize/)(double) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [set_Modified](../../aspose.pdf.annotations/annotation/set_modified/)(System::DateTime) | Sets date and time when annotation was recently modified. |
| [set_Name](../../aspose.pdf.annotations/annotation/set_name/)(System::String) | Sets annotation name on the page. |
| [set_OnActivated](../../aspose.pdf.annotations/widgetannotation/set_onactivated/)(System::SharedPtr\<PdfAction\>) | An action which shall be performed when the annotation is activated. |
| [set_PartialName](./set_partialname/)(System::String) | Sets partial name of the field. |
| [set_ReadOnly](../../aspose.pdf.annotations/widgetannotation/set_readonly/)(bool) | Sets read only status of the field. |
| [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) override | Sets the field rectangle. |
| [set_Required](../../aspose.pdf.annotations/widgetannotation/set_required/)(bool) | Sets required status of the field. |
| [set_TabOrder](./set_taborder/)(int32_t) | Sets tab order of the field. |
| [set_TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/set_texthorizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets text alignment for annotation. |
| static [set_UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/set_updateappearanceonconvert/)(bool) | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [set_UseFontSubset](../../aspose.pdf.annotations/annotation/set_usefontsubset/)(bool) | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [set_Value](./set_value/)(System::String) | Sets value of the field. |
| virtual [set_VerticalAlignment](../../aspose.pdf/baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| virtual [set_Width](../../aspose.pdf.annotations/annotation/set_width/)(double) | Sets width of the annotation. |
| [set_ZIndex](../../aspose.pdf/baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| virtual [SetPosition](./setposition/)(System::SharedPtr\<Point\>) | Set position of the field. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/widgetannotation/)(System::SharedPtr\<Document\>) | Create annotation (used for Generator) |
## See Also

* Class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
