---
title: Aspose::Pdf::Artifact class
linktitle: Artifact
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Artifact class. Class represents PDF Artifact object in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf/artifact/
---
## Artifact class


Class represents PDF [Artifact](./) object.

```cpp
class Artifact : public System::IDisposable
```

## Enums

| Enum | Description |
| --- | --- |
| [ArtifactSubtype](./artifactsubtype/) | Enumeration of possible artifacts subtype. |
| [ArtifactType](./artifacttype/) | Enumeration of possible artifact types. |
## Methods

| Method | Description |
| --- | --- |
| [Artifact](./artifact/)(System::String, System::String) | Constructor of artifact with specified type and subtype. |
| [Artifact](./artifact/)(Artifact::ArtifactType, Artifact::ArtifactSubtype) | Constructor of artifact with specified type and subtype. |
| [BeginUpdates](./beginupdates/)() | Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed anytime when artifact property was changed. This causes changing of page contents everytime when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls. This allows to change page contents only once. |
| [Dispose](./dispose/)() override | Dispose the artifact. |
| [get_ArtifactHorizontalAlignment](./get_artifacthorizontalalignment/)() const | Horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_ArtifactVerticalAlignment](./get_artifactverticalalignment/)() const | Vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_BottomMargin](./get_bottommargin/)() const | Bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_Contents](./get_contents/)() | Gets collection of artifact internal operators. |
| [get_CustomSubtype](./get_customsubtype/)() | Gets name of artifact subtype. May be used if artifact subtype is not standard subtype. |
| [get_CustomType](./get_customtype/)() | Gets name of artifact type. May be used if artifact type is non standard. |
| [get_Form](./get_form/)() | Gets [XForm](../xform/) of the artifact (if [XForm](../xform/) is used). |
| [get_Image](./get_image/)() | Gets image of the artifact (if presents). |
| [get_IsBackground](./get_isbackground/)() const | If true [Artifact](./) is placed behind page contents. |
| [get_LeftMargin](./get_leftmargin/)() const | [Left](../left/) margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_Lines](./get_lines/)() | Lines of multiline text artifact. |
| [get_Opacity](./get_opacity/)() const | Gets opacity of the artifact. Possible values are in range 0..1. |
| [get_Position](./get_position/)() const | Gets artifact position. If this property is specified, then margins and alignments are ignored. |
| [get_Rectangle](./get_rectangle/)() | Gets rectangle of the artifact. |
| [get_RightMargin](./get_rightmargin/)() const | [Right](../right/) margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_Rotation](./get_rotation/)() | Gets artifact rotation angle. |
| [get_Subtype](./get_subtype/)() | Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype. |
| [get_Text](./get_text/)() | Gets text of the artifact. |
| [get_TextState](./get_textstate/)() | [Text](../../aspose.pdf.text/) state for artifact text. |
| [get_TopMargin](./get_topmargin/)() const | Top margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_Type](./get_type/)() | Gets artifact type. |
| [GetValue](./getvalue/)(System::String) | Gets custom value of artifact. |
| [RemoveValue](./removevalue/)(System::String) | Remove custom value from the artifact. |
| [SaveUpdates](./saveupdates/)() | Saves all updates in artifact which were made after [BeginUpdates()](./beginupdates/) call. |
| [set_ArtifactHorizontalAlignment](./set_artifacthorizontalalignment/)(HorizontalAlignment) | Horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_ArtifactVerticalAlignment](./set_artifactverticalalignment/)(VerticalAlignment) | Vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_BottomMargin](./set_bottommargin/)(double) | Bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_CustomSubtype](./set_customsubtype/)(System::String) | Gets name of artifact subtype. May be used if artifact subtype is not standard subtype. |
| [set_CustomType](./set_customtype/)(System::String) | Gets name of artifact type. May be used if artifact type is non standard. |
| [set_IsBackground](./set_isbackground/)(bool) | If true [Artifact](./) is placed behind page contents. |
| [set_LeftMargin](./set_leftmargin/)(double) | [Left](../left/) margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_Opacity](./set_opacity/)(double) | Sets opacity of the artifact. Possible values are in range 0..1. |
| [set_Position](./set_position/)(System::SharedPtr\<Point\>) | Sets artifact position. If this property is specified, then margins and alignments are ignored. |
| [set_RightMargin](./set_rightmargin/)(double) | [Right](../right/) margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_Rotation](./set_rotation/)(double) | Sets artifact rotation angle. |
| [set_Subtype](./set_subtype/)(Artifact::ArtifactSubtype) | Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype. |
| [set_Text](./set_text/)(System::String) | Gets text of the artifact. |
| [set_TextState](./set_textstate/)(System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | [Text](../../aspose.pdf.text/) state for artifact text. |
| [set_TopMargin](./set_topmargin/)(double) | Top margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_Type](./set_type/)(Artifact::ArtifactType) | Gets artifact type. |
| [SetImage](./setimage/)(System::SharedPtr\<System::IO::Stream\>) | Sets image of the artifact. |
| [SetImage](./setimage/)(System::String) | Sets image of the artifact. |
| [SetLinesAndState](./setlinesandstate/)(System::ArrayPtr\<System::String\>, System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Set text and text properties of the artifact. Allows to specify multiple lines. |
| [SetPageNumberReplacementString](./setpagenumberreplacementstring/)(System::String) | Sets what string will be replaced with the page number. The default value is #. |
| [SetPdfPage](./setpdfpage/)(System::SharedPtr\<Page\>) | Sets PDF page which is placed on the document page as artifact. |
| [SetText](./settext/)(System::SharedPtr\<Facades::FormattedText\>) | Sets text of the artifact. |
| [SetTextAndState](./settextandstate/)(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Set text and text properties of the artifact. |
| [SetValue](./setvalue/)(System::String, System::String) | Sets custom value of artifact. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
