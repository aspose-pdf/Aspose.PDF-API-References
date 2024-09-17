---
title: Aspose::Pdf::Forms::RadioButtonField class
linktitle: RadioButtonField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::RadioButtonField class. Class representing radio button field in C++.'
type: docs
weight: 2100
url: /cpp/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class


Class representing radio button field.

```cpp
class RadioButtonField : public Aspose::Pdf::Forms::ChoiceField
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor. |
| [Add](./add/)(const System::SharedPtr\<RadioButtonOptionField\>\&) | Adds new option field to RadioButton field. |
| [AddOption](./addoption/)(System::String, System::SharedPtr\<Rectangle\>) | Add to radio button option with specifed rectangle. |
| [AddOption](./addoption/)(System::String) override | Add option to radion button. |
| virtual [AddOption](../choicefield/addoption/)(System::String, System::String) | Adds new option with specified export value and name. |
| [BaseParagraph](../../aspose.pdf/baseparagraph/baseparagraph/)() |  |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(System::SharedPtr\<Matrix\>) | Update parameters and appearance, according to the matrix transform. |
| [ChoiceField](../choicefield/choicefield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Constructor for [ChoiceField](../choicefield/). |
| [ChoiceField](../choicefield/choicefield/)(System::SharedPtr\<Document\>) | Creates choice field (for Generator) |
| [ChoiceField](../choicefield/choicefield/)(System::SharedPtr\<Document\>, System::SharedPtr\<Rectangle\>) | Constructor for [ChoiceField](../choicefield/). |
| [Clone](../../aspose.pdf/baseparagraph/clone/)() override | Clones this instance. Virtual method. Always return null. |
| [CopyTo](../field/copyto/)(System::ArrayPtr\<System::SharedPtr\<Field\>\>, int32_t) | Copies subfields of this field into array starting from specified index. |
| [CopyToWidgetArray](../field/copytowidgetarray/)(System::ArrayPtr\<System::SharedPtr\<Aspose::Pdf::Annotations::WidgetAnnotation\>\>, int32_t) | Copies subfields of this field into array starting from specified index. |
| virtual [DeleteOption](../choicefield/deleteoption/)(System::String) | Deletes option by its name. |
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
| [get_CommitImmediately](../choicefield/get_commitimmediately/)() | Gets commit on selection change flag. |
| [get_Contents](../../aspose.pdf.annotations/annotation/get_contents/)() | Gets annotation text. |
| [get_Count](../field/get_count/)() const override | Gets number of subfields in this field. (For example number of items in radio button field). |
| [get_DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/get_defaultappearance/)() | Gets default appearance of the field. |
| [get_Exportable](../../aspose.pdf.annotations/widgetannotation/get_exportable/)() | Gets exportable flag of the field. |
| static [get_FitIntoRectangle](../field/get_fitintorectangle/)() | If true then font size will reduced to fit text to specified rectangle. |
| [get_Flags](../../aspose.pdf.annotations/annotation/get_flags/)() | Flags of the annotation. |
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
| [get_MappingName](../field/get_mappingname/)() | Gets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [get_Margin](../../aspose.pdf/baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| static [get_MaxFontSize](../field/get_maxfontsize/)() | Maximail font size which can be used for field contents. -1 to don't check size. |
| static [get_MinFontSize](../field/get_minfontsize/)() | Minimal font size which can be used for field contents. -1 to don't check size. |
| [get_Modified](../../aspose.pdf.annotations/annotation/get_modified/)() | Gets date and time when annotation was recently modified. |
| [get_MultiSelect](../choicefield/get_multiselect/)() | Gets multiselection flag. |
| [get_Name](../../aspose.pdf.annotations/annotation/get_name/)() | Gets annotation name on the page. |
| [get_NoToggleToOff](./get_notoggletooff/)() | Get or sets the flag that allows the radiobutton to have no selected value. If **true**

, exactly one radio button shall be selected at all times; selecting the currently selected button has no effect. If **false**

, clicking the selected button deselects it, leaving no button selected. |
| [get_OnActivated](../../aspose.pdf.annotations/widgetannotation/get_onactivated/)() | An action which shall be performed when the annotation is activated. |
| [get_Options](./get_options/)() override | Gets collection of options of the radio button. |
| [get_PageIndex](./get_pageindex/)() override | Gets index of page which contains this RadioButton field. |
| [get_Parent](../../aspose.pdf.annotations/widgetannotation/get_parent/)() | Gets annotation parent. |
| [get_PartialName](../field/get_partialname/)() | Gets partial name of the field. |
| [get_ReadOnly](../../aspose.pdf.annotations/widgetannotation/get_readonly/)() | Gets read only status of the field. |
| [get_Rect](../field/get_rect/)() override | Gets the field rectangle. |
| [get_Required](../../aspose.pdf.annotations/widgetannotation/get_required/)() | Gets required status of the field. |
| [get_Selected](./get_selected/)() override | Gets index of selected item. Numbering of items is started from 1. |
| virtual [get_SelectedItems](../choicefield/get_selecteditems/)() | Gets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item. |
| [get_States](../../aspose.pdf.annotations/annotation/get_states/)() | Gets appearance dictionary of annotation. |
| [get_Style](./get_style/)() | Style of field box. |
| [get_SyncRoot](../field/get_syncroot/)() const | Synchronization object. |
| [get_TabOrder](../field/get_taborder/)() | Gets tab order of the field. |
| [get_TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/get_texthorizontalalignment/)() | Gets text alignment for annotation. |
| static [get_UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/get_updateappearanceonconvert/)() | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [get_UseFontSubset](../../aspose.pdf.annotations/annotation/get_usefontsubset/)() | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| [get_Value](./get_value/)() override | Gets value of field. |
| virtual [get_VerticalAlignment](../../aspose.pdf/baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| virtual [get_Width](../../aspose.pdf.annotations/annotation/get_width/)() | Gets width of the annotation. |
| [get_ZIndex](../../aspose.pdf/baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Returns name of "checked" state according to existing state names. |
| [GetEnumerator](../field/getenumerator/)() override | Returns enumerator of contained fields. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [idx_get](../field/idx_get/)(System::String) | Gets subfield contained in this field by name of the subfield. |
| [idx_get](../field/idx_get/)(int32_t) | Gets subfield contained in this field by index. |
| [RadioButtonField](./radiobuttonfield/)(System::SharedPtr\<Aspose::Pdf::Page\>) | Constructor for RadiouttonField. |
| [RadioButtonField](./radiobuttonfield/)(System::SharedPtr\<Document\>) | Constructor for [RadioButtonField](./). |
| [Recalculate](../field/recalculate/)() | Recaculates all calculated fields on the form. |
| virtual [set_ActiveState](../../aspose.pdf.annotations/annotation/set_activestate/)(System::String) | Sets current annotation appearance state. |
| [set_Alignment](../../aspose.pdf.annotations/annotation/set_alignment/)(TextAlignment) | [Annotation](../../aspose.pdf.annotations/annotation/) alignment. This property is obsolete. Use HorizontalAligment instead. |
| [set_AlternateName](../field/set_alternatename/)(System::String) | Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [set_AnnotationIndex](../field/set_annotationindex/)(int32_t) | Sets index of this anotation on the page. |
| [set_Border](../../aspose.pdf.annotations/annotation/set_border/)(System::SharedPtr\<Aspose::Pdf::Annotations::Border\>) | Sets annotation border characteristics. [Border](../../aspose.pdf.annotations/border/) |
| [set_Color](../../aspose.pdf.annotations/annotation/set_color/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets annotation color. |
| [set_CommitImmediately](../choicefield/set_commitimmediately/)(bool) | Sets commit on selection change flag. |
| [set_Contents](../../aspose.pdf.annotations/annotation/set_contents/)(System::String) | Sets annotation text. |
| [set_DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/set_defaultappearance/)(System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>) | Sets default appearance of the field. |
| [set_Exportable](../../aspose.pdf.annotations/widgetannotation/set_exportable/)(bool) | Sets exportable flag of the field. |
| static [set_FitIntoRectangle](../field/set_fitintorectangle/)(bool) | If true then font size will reduced to fit text to specified rectangle. |
| [set_Flags](../../aspose.pdf.annotations/annotation/set_flags/)(AnnotationFlags) | Flags of the annotation. |
| virtual [set_Height](../../aspose.pdf.annotations/annotation/set_height/)(double) | Sets height of the annotation. |
| [set_Highlighting](../../aspose.pdf.annotations/widgetannotation/set_highlighting/)(HighlightingMode) | [Annotation](../../aspose.pdf.annotations/annotation/) highlighting mode. |
| [set_HorizontalAlignment](../../aspose.pdf.annotations/annotation/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Sets text alignment for annotation. |
| virtual [set_Hyperlink](../../aspose.pdf/baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../../aspose.pdf/baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../../aspose.pdf/baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../../aspose.pdf/baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_IsSharedField](../field/set_issharedfield/)(bool) | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [set_MappingName](../field/set_mappingname/)(System::String) | Sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [set_Margin](../../aspose.pdf/baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| static [set_MaxFontSize](../field/set_maxfontsize/)(double) | Maximail font size which can be used for field contents. -1 to don't check size. |
| static [set_MinFontSize](../field/set_minfontsize/)(double) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [set_Modified](../../aspose.pdf.annotations/annotation/set_modified/)(System::DateTime) | Sets date and time when annotation was recently modified. |
| [set_MultiSelect](../choicefield/set_multiselect/)(bool) | Sets multiselection flag. |
| [set_Name](../../aspose.pdf.annotations/annotation/set_name/)(System::String) | Sets annotation name on the page. |
| [set_NoToggleToOff](./set_notoggletooff/)(bool) | Get or sets the flag that allows the radiobutton to have no selected value. If **true**

, exactly one radio button shall be selected at all times; selecting the currently selected button has no effect. If **false**

, clicking the selected button deselects it, leaving no button selected. |
| [set_OnActivated](../../aspose.pdf.annotations/widgetannotation/set_onactivated/)(System::SharedPtr\<PdfAction\>) | An action which shall be performed when the annotation is activated. |
| [set_PartialName](../field/set_partialname/)(System::String) | Sets partial name of the field. |
| [set_ReadOnly](../../aspose.pdf.annotations/widgetannotation/set_readonly/)(bool) | Sets read only status of the field. |
| [set_Rect](../field/set_rect/)(System::SharedPtr\<Rectangle\>) override | Sets the field rectangle. |
| [set_Required](../../aspose.pdf.annotations/widgetannotation/set_required/)(bool) | Sets required status of the field. |
| [set_Selected](./set_selected/)(int32_t) override | Sets index of selected item. Numbering of items is started from 1. |
| virtual [set_SelectedItems](../choicefield/set_selecteditems/)(System::ArrayPtr\<int32_t\>) | Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item. |
| [set_Style](./set_style/)(BoxStyle) | Style of field box. |
| [set_TabOrder](../field/set_taborder/)(int32_t) | Sets tab order of the field. |
| [set_TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/set_texthorizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets text alignment for annotation. |
| static [set_UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/set_updateappearanceonconvert/)(bool) | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [set_UseFontSubset](../../aspose.pdf.annotations/annotation/set_usefontsubset/)(bool) | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| [set_Value](./set_value/)(System::String) override | Sets value of field. |
| virtual [set_VerticalAlignment](../../aspose.pdf/baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| virtual [set_Width](../../aspose.pdf.annotations/annotation/set_width/)(double) | Sets width of the annotation. |
| [set_ZIndex](../../aspose.pdf/baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [SetPosition](./setposition/)(System::SharedPtr\<Point\>) override | Move all subitems of radio button to specified positins on the page. |
| [SetTemplateWeakPtr](../field/settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/widgetannotation/)(System::SharedPtr\<Document\>) | Create annotation (used for Generator) |
## See Also

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
