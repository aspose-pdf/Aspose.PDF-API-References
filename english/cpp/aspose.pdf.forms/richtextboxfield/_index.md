---
title: Aspose::Pdf::Forms::RichTextBoxField class
linktitle: RichTextBoxField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::RichTextBoxField class. Class describes rich text editor component in C++.'
type: docs
weight: 2300
url: /cpp/aspose.pdf.forms/richtextboxfield/
---
## RichTextBoxField class


Class describes rich text editor component.

```cpp
class RichTextBoxField : public Aspose::Pdf::Forms::TextBoxField
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor. |
| [AddBarcode](../textboxfield/addbarcode/)(System::String) | Adds barcode 128 into the field. [Field](../field/) value will be changed onto the code and field become read only. |
| [AddImage](../textboxfield/addimage/)(System::SharedPtr\<System::Drawing::Image\>) | Adds image into the field resources and draws it. |
| [BaseParagraph](../../aspose.pdf/baseparagraph/baseparagraph/)() |  |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(System::SharedPtr\<Matrix\>) | Update parameters and appearance, according to the matrix transform. |
| [Clone](../../aspose.pdf/baseparagraph/clone/)() override | Clones this instance. Virtual method. Always return null. |
| [CopyTo](../field/copyto/)(System::ArrayPtr\<System::SharedPtr\<Field\>\>, int32_t) | Copies subfields of this field into array starting from specified index. |
| [CopyToWidgetArray](../field/copytowidgetarray/)(System::ArrayPtr\<System::SharedPtr\<Aspose::Pdf::Annotations::WidgetAnnotation\>\>, int32_t) | Copies subfields of this field into array starting from specified index. |
| [ExecuteFieldJavaScript](../field/executefieldjavascript/)(System::SharedPtr\<Aspose::Pdf::Annotations::JavascriptAction\>) | Executes a specified JavaScript action for the field. |
| [Field](../field/field/)(System::SharedPtr\<Document\>) | Creates field for use in Generator. |
| [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [get_Actions](../../aspose.pdf.annotations/widgetannotation/get_actions/)() const | Gets the annotation actions. |
| [get_Actions](../../aspose.pdf.annotations/annotation/get_actions/)() | Gets list of annotatation actions. |
| virtual [get_ActiveState](../../aspose.pdf.annotations/annotation/get_activestate/)() | Gets current annotation appearance state. |
| [get_Alignment](../../aspose.pdf.annotations/annotation/get_alignment/)() | [Annotation](../../aspose.pdf.annotations/annotation/) alignment. This property is obsolete. Use HorizontalAligment instead. |
| [get_AlternateName](../field/get_alternatename/)() | Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [get_AnnotationIndex](../field/get_annotationindex/)() | Gets index of this anotation on the page. |
| [get_AnnotationType](../../aspose.pdf.annotations/widgetannotation/get_annotationtype/)() override | Gets type of annotation. |
| [get_Appearance](../../aspose.pdf.annotations/annotation/get_appearance/)() | Gets appearance dictionary of the annotation. |
| [get_Border](../../aspose.pdf.annotations/annotation/get_border/)() const | Gets annotation border characteristics. [Border](../../aspose.pdf.annotations/border/) |
| [get_Characteristics](../../aspose.pdf.annotations/annotation/get_characteristics/)() | Gets annotation characteristics. |
| [get_Color](../../aspose.pdf.annotations/annotation/get_color/)() | Gets annotation color. |
| [get_Contents](../../aspose.pdf.annotations/annotation/get_contents/)() | Gets annotation text. |
| [get_Count](../field/get_count/)() const override | Gets number of subfields in this field. (For example number of items in radio button field). |
| [get_DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/get_defaultappearance/)() | Gets default appearance of the field. |
| [get_Exportable](../../aspose.pdf.annotations/widgetannotation/get_exportable/)() | Gets exportable flag of the field. |
| static [get_FitIntoRectangle](../field/get_fitintorectangle/)() | If true then font size will reduced to fit text to specified rectangle. |
| [get_Flags](../../aspose.pdf.annotations/annotation/get_flags/)() | Flags of the annotation. |
| [get_ForceCombs](../textboxfield/get_forcecombs/)() | Gets flag which indicates is field divided into spaced positions. |
| [get_FormattedValue](./get_formattedvalue/)() | Gets formatted rich text value with markup. |
| [get_FullName](../../aspose.pdf.annotations/annotation/get_fullname/)() | Gets full qualified name of the annotation. |
| virtual [get_Height](../../aspose.pdf.annotations/annotation/get_height/)() | Gets height of the annotation. |
| [get_Highlighting](../../aspose.pdf.annotations/widgetannotation/get_highlighting/)() | [Annotation](../../aspose.pdf.annotations/annotation/) highlighting mode. |
| [get_HorizontalAlignment](../../aspose.pdf.annotations/annotation/get_horizontalalignment/)() override | Gets text alignment for annotation. |
| virtual [get_Hyperlink](../../aspose.pdf/baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsGroup](../field/get_isgroup/)() const | Gets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [get_IsInLineParagraph](../../aspose.pdf/baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../../aspose.pdf/baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../../aspose.pdf/baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_IsSharedField](../field/get_issharedfield/)() const | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [get_IsSynchronized](../field/get_issynchronized/)() | Returns true if dictionary is synchronized. |
| [get_Justify](./get_justify/)() | Gets justification of the rich text box. |
| [get_MappingName](../field/get_mappingname/)() | Gets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [get_Margin](../../aspose.pdf/baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| static [get_MaxFontSize](../field/get_maxfontsize/)() | Maximail font size which can be used for field contents. -1 to don't check size. |
| [get_MaxLen](../textboxfield/get_maxlen/)() | Gets maximum length of text in the field. |
| static [get_MinFontSize](../field/get_minfontsize/)() | Minimal font size which can be used for field contents. -1 to don't check size. |
| [get_Modified](../../aspose.pdf.annotations/annotation/get_modified/)() | Gets date and time when annotation was recently modified. |
| [get_Multiline](../textboxfield/get_multiline/)() | Gets multiline flag of the field. If Multiline is true field can contain multiple lines of text. |
| [get_Name](../../aspose.pdf.annotations/annotation/get_name/)() | Gets annotation name on the page. |
| [get_OnActivated](../../aspose.pdf.annotations/widgetannotation/get_onactivated/)() | An action which shall be performed when the annotation is activated. |
| [get_PageIndex](../field/get_pageindex/)() override | Gets index of page which contains this field. |
| [get_Parent](../../aspose.pdf.annotations/widgetannotation/get_parent/)() | Gets annotation parent. |
| [get_PartialName](../field/get_partialname/)() | Gets partial name of the field. |
| [get_ReadOnly](../../aspose.pdf.annotations/widgetannotation/get_readonly/)() | Gets read only status of the field. |
| [get_Rect](../field/get_rect/)() override | Gets the field rectangle. |
| [get_Required](../../aspose.pdf.annotations/widgetannotation/get_required/)() | Gets required status of the field. |
| [get_RichTextValue](./get_richtextvalue/)() | Gets rich text value. |
| [get_Scrollable](../textboxfield/get_scrollable/)() | Gets scrollable flag of field. If true field can be scrolled. |
| [get_SpellCheck](../textboxfield/get_spellcheck/)() | Gets spellcheck flag for field. If true field shall be spell checked. |
| [get_States](../../aspose.pdf.annotations/annotation/get_states/)() | Gets appearance dictionary of annotation. |
| [get_Style](./get_style/)() | Gets default style string of the rich text field. |
| [get_SyncRoot](../field/get_syncroot/)() const | Synchronization object. |
| [get_TabOrder](../field/get_taborder/)() | Gets tab order of the field. |
| [get_TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/get_texthorizontalalignment/)() | Gets text alignment for annotation. |
| [get_TextVerticalAlignment](../textboxfield/get_textverticalalignment/)() const | Gets text vertical alignment for annotation. |
| static [get_UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/get_updateappearanceonconvert/)() | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [get_UseFontSubset](../../aspose.pdf.annotations/annotation/get_usefontsubset/)() | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| [get_Value](./get_value/)() override | Value of RichTextField. |
| virtual [get_VerticalAlignment](../../aspose.pdf/baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| virtual [get_Width](../../aspose.pdf.annotations/annotation/get_width/)() | Gets width of the annotation. |
| [get_ZIndex](../../aspose.pdf/baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returns name of "checked" state according to existing state names. |
| [GetEnumerator](../field/getenumerator/)() override | Returns enumerator of contained fields. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [idx_get](../field/idx_get/)(System::String) | Gets subfield contained in this field by name of the subfield. |
| [idx_get](../field/idx_get/)(int32_t) | Gets subfield contained in this field by index. |
| [Recalculate](../field/recalculate/)() | Recaculates all calculated fields on the form. |
| [RichTextBoxField](./richtextboxfield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Constructor for Rich [Text](../../aspose.pdf.text/) Box field. |
| virtual [set_ActiveState](../../aspose.pdf.annotations/annotation/set_activestate/)(System::String) | Sets current annotation appearance state. |
| [set_Alignment](../../aspose.pdf.annotations/annotation/set_alignment/)(TextAlignment) | [Annotation](../../aspose.pdf.annotations/annotation/) alignment. This property is obsolete. Use HorizontalAligment instead. |
| [set_AlternateName](../field/set_alternatename/)(System::String) | Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [set_AnnotationIndex](../field/set_annotationindex/)(int32_t) | Sets index of this anotation on the page. |
| [set_Border](../../aspose.pdf.annotations/annotation/set_border/)(System::SharedPtr\<Aspose::Pdf::Annotations::Border\>) | Sets annotation border characteristics. [Border](../../aspose.pdf.annotations/border/) |
| [set_Color](../../aspose.pdf.annotations/annotation/set_color/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets annotation color. |
| [set_Contents](../../aspose.pdf.annotations/annotation/set_contents/)(System::String) | Sets annotation text. |
| [set_DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/set_defaultappearance/)(System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>) | Sets default appearance of the field. |
| [set_Exportable](../../aspose.pdf.annotations/widgetannotation/set_exportable/)(bool) | Sets exportable flag of the field. |
| static [set_FitIntoRectangle](../field/set_fitintorectangle/)(bool) | If true then font size will reduced to fit text to specified rectangle. |
| [set_Flags](../../aspose.pdf.annotations/annotation/set_flags/)(AnnotationFlags) | Flags of the annotation. |
| [set_ForceCombs](../textboxfield/set_forcecombs/)(bool) | Sets flag which indicates is field divided into spaced positions. |
| [set_FormattedValue](./set_formattedvalue/)(System::String) | Sets formatted rich text value with markup. |
| virtual [set_Height](../../aspose.pdf.annotations/annotation/set_height/)(double) | Sets height of the annotation. |
| [set_Highlighting](../../aspose.pdf.annotations/widgetannotation/set_highlighting/)(HighlightingMode) | [Annotation](../../aspose.pdf.annotations/annotation/) highlighting mode. |
| [set_HorizontalAlignment](../../aspose.pdf.annotations/annotation/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Sets text alignment for annotation. |
| virtual [set_Hyperlink](../../aspose.pdf/baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../../aspose.pdf/baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../../aspose.pdf/baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../../aspose.pdf/baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_IsSharedField](../field/set_issharedfield/)(bool) | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [set_Justify](./set_justify/)(Aspose::Pdf::Annotations::Justification) | Sets justification of the rich text box. |
| [set_MappingName](../field/set_mappingname/)(System::String) | Sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [set_Margin](../../aspose.pdf/baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| static [set_MaxFontSize](../field/set_maxfontsize/)(double) | Maximail font size which can be used for field contents. -1 to don't check size. |
| [set_MaxLen](../textboxfield/set_maxlen/)(int32_t) | Sets maximum length of text in the field. |
| static [set_MinFontSize](../field/set_minfontsize/)(double) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [set_Modified](../../aspose.pdf.annotations/annotation/set_modified/)(System::DateTime) | Sets date and time when annotation was recently modified. |
| [set_Multiline](../textboxfield/set_multiline/)(bool) | Sets multiline flag of the field. If Multiline is true field can contain multiple lines of text. |
| [set_Name](../../aspose.pdf.annotations/annotation/set_name/)(System::String) | Sets annotation name on the page. |
| [set_OnActivated](../../aspose.pdf.annotations/widgetannotation/set_onactivated/)(System::SharedPtr\<PdfAction\>) | An action which shall be performed when the annotation is activated. |
| [set_PartialName](../field/set_partialname/)(System::String) | Sets partial name of the field. |
| [set_ReadOnly](../../aspose.pdf.annotations/widgetannotation/set_readonly/)(bool) | Sets read only status of the field. |
| [set_Rect](../field/set_rect/)(System::SharedPtr\<Rectangle\>) override | Sets the field rectangle. |
| [set_Required](../../aspose.pdf.annotations/widgetannotation/set_required/)(bool) | Sets required status of the field. |
| [set_RichTextValue](./set_richtextvalue/)(System::String) | Sets rich text value. |
| [set_Scrollable](../textboxfield/set_scrollable/)(bool) | Sets scrollable flag of field. If true field can be scrolled. |
| [set_SpellCheck](../textboxfield/set_spellcheck/)(bool) | Sets spellcheck flag for field. If true field shall be spell checked. |
| [set_Style](./set_style/)(System::String) | Sets default style string of the rich text field. |
| [set_TabOrder](../field/set_taborder/)(int32_t) | Sets tab order of the field. |
| [set_TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/set_texthorizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets text alignment for annotation. |
| [set_TextVerticalAlignment](../textboxfield/set_textverticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets text vertical alignment for annotation. |
| static [set_UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/set_updateappearanceonconvert/)(bool) | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [set_UseFontSubset](../../aspose.pdf.annotations/annotation/set_usefontsubset/)(bool) | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| [set_Value](./set_value/)(System::String) override | Value of RichTextField. |
| virtual [set_VerticalAlignment](../../aspose.pdf/baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| virtual [set_Width](../../aspose.pdf.annotations/annotation/set_width/)(double) | Sets width of the annotation. |
| [set_ZIndex](../../aspose.pdf/baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| virtual [SetPosition](../field/setposition/)(System::SharedPtr\<Point\>) | Set position of the field. |
| [SetTemplateWeakPtr](../field/settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [TextBoxField](../textboxfield/textboxfield/)(System::SharedPtr\<Document\>) | Constructor which should be used with Generator. |
| [TextBoxField](../textboxfield/textboxfield/)() | Create instance of [TextBoxField](../textboxfield/). |
| [TextBoxField](../textboxfield/textboxfield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Constructor of TextBox field. |
| [TextBoxField](../textboxfield/textboxfield/)(System::SharedPtr\<Document\>, System::SharedPtr\<Rectangle\>) | Constructor of TextBox field. |
| [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/widgetannotation/)(System::SharedPtr\<Document\>) | Create annotation (used for Generator) |
## See Also

* Class [TextBoxField](../textboxfield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
