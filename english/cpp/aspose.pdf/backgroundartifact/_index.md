---
title: Aspose::Pdf::BackgroundArtifact class
linktitle: BackgroundArtifact
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::BackgroundArtifact class. Class descibes background artifact. This artifact allows to set background of the page in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/backgroundartifact/
---
## BackgroundArtifact class


Class descibes background artifact. This artifact allows to set background of the page.

```cpp
class BackgroundArtifact : public Aspose::Pdf::Artifact
```

## Methods

| Method | Description |
| --- | --- |
| [Artifact](../artifact/artifact/)(System::String, System::String) | Constructor of artifact with specified type and subtype. |
| [Artifact](../artifact/artifact/)(Artifact::ArtifactType, Artifact::ArtifactSubtype) | Constructor of artifact with specified type and subtype. |
| [BackgroundArtifact](./backgroundartifact/)() | Initializes [BackgroundArtifact](./) object. |
| [BeginUpdates](../artifact/beginupdates/)() | Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed anytime when artifact property was changed. This causes changing of page contents everytime when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls. This allows to change page contents only once. |
| [Dispose](../artifact/dispose/)() override | Dispose the artifact. |
| [get_ArtifactHorizontalAlignment](../artifact/get_artifacthorizontalalignment/)() const | Horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_ArtifactVerticalAlignment](../artifact/get_artifactverticalalignment/)() const | Vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Gets bacground color of background artifact. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Gets bacground image of background artifact. |
| [get_BottomMargin](../artifact/get_bottommargin/)() const | Bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_Contents](../artifact/get_contents/)() | Gets collection of artifact internal operators. |
| [get_CustomSubtype](../artifact/get_customsubtype/)() | Gets name of artifact subtype. May be used if artifact subtype is not standard subtype. |
| [get_CustomType](../artifact/get_customtype/)() | Gets name of artifact type. May be used if artifact type is non standard. |
| [get_Form](../artifact/get_form/)() | Gets [XForm](../xform/) of the artifact (if [XForm](../xform/) is used). |
| [get_Image](../artifact/get_image/)() | Gets image of the artifact (if presents). |
| [get_IsBackground](../artifact/get_isbackground/)() const | If true [Artifact](../artifact/) is placed behind page contents. |
| [get_LeftMargin](../artifact/get_leftmargin/)() const | Left margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_Lines](../artifact/get_lines/)() | Lines of multiline text artifact. |
| [get_Opacity](../artifact/get_opacity/)() const | Gets opacity of the artifact. Possible values are in range 0..1. |
| [get_Position](../artifact/get_position/)() const | Gets artifact position. If this property is specified, then margins and alignments are ignored. |
| [get_Rectangle](../artifact/get_rectangle/)() | Gets rectangle of the artifact. |
| [get_RightMargin](../artifact/get_rightmargin/)() const | Right margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_Rotation](../artifact/get_rotation/)() | Gets artifact rotation angle. |
| [get_Subtype](../artifact/get_subtype/)() | Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype. |
| [get_Text](../artifact/get_text/)() | Gets text of the artifact. |
| [get_TextState](../artifact/get_textstate/)() const | [Text](../../aspose.pdf.text/) state for artifact text. |
| [get_TopMargin](../artifact/get_topmargin/)() const | Top margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [get_Type](../artifact/get_type/)() | Gets artifact type. |
| [GetValue](../artifact/getvalue/)(System::String) | Gets custom value of artifact. |
| [RemoveValue](../artifact/removevalue/)(System::String) | Remove custom value from the artifact. |
| [SaveUpdates](../artifact/saveupdates/)() | Saves all updates in artifact which were made after [BeginUpdates()](../artifact/beginupdates/) call. |
| [set_ArtifactHorizontalAlignment](../artifact/set_artifacthorizontalalignment/)(HorizontalAlignment) | Horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_ArtifactVerticalAlignment](../artifact/set_artifactverticalalignment/)(VerticalAlignment) | Vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets bacground color of background artifact. |
| [set_BackgroundImage](./set_backgroundimage/)(System::SharedPtr\<System::IO::Stream\>) | Sets bacground image of background artifact. |
| [set_BottomMargin](../artifact/set_bottommargin/)(double) | Bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_CustomSubtype](../artifact/set_customsubtype/)(System::String) | Gets name of artifact subtype. May be used if artifact subtype is not standard subtype. |
| [set_CustomType](../artifact/set_customtype/)(System::String) | Gets name of artifact type. May be used if artifact type is non standard. |
| [set_IsBackground](../artifact/set_isbackground/)(bool) | If true [Artifact](../artifact/) is placed behind page contents. |
| [set_LeftMargin](../artifact/set_leftmargin/)(double) | Left margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_Opacity](../artifact/set_opacity/)(double) | Sets opacity of the artifact. Possible values are in range 0..1. |
| [set_Position](../artifact/set_position/)(System::SharedPtr\<Point\>) | Sets artifact position. If this property is specified, then margins and alignments are ignored. |
| [set_RightMargin](../artifact/set_rightmargin/)(double) | Right margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_Rotation](../artifact/set_rotation/)(double) | Sets artifact rotation angle. |
| [set_Subtype](../artifact/set_subtype/)(Artifact::ArtifactSubtype) | Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype. |
| [set_Text](../artifact/set_text/)(System::String) | Gets text of the artifact. |
| [set_TextState](../artifact/set_textstate/)(System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | [Text](../../aspose.pdf.text/) state for artifact text. |
| [set_TopMargin](../artifact/set_topmargin/)(double) | Top margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [set_Type](../artifact/set_type/)(Artifact::ArtifactType) | Gets artifact type. |
| [SetImage](../artifact/setimage/)(System::SharedPtr\<System::IO::Stream\>) | Sets image of the artifact. |
| [SetImage](../artifact/setimage/)(System::String) | Sets image of the artifact. |
| [SetLinesAndState](../artifact/setlinesandstate/)(System::ArrayPtr\<System::String\>, System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Set text and text properties of the artifact. Allows to specify multiple lines. |
| [SetPageNumberReplacementString](../artifact/setpagenumberreplacementstring/)(System::String) | Sets what string will be replaced with the page number. The default value is #. |
| [SetPdfPage](../artifact/setpdfpage/)(System::SharedPtr\<Page\>) | Sets PDF page which is placed on the document page as artifact. |
| [SetText](../artifact/settext/)(System::SharedPtr\<Facades::FormattedText\>) | Sets text of the artifact. |
| [SetTextAndState](../artifact/settextandstate/)(System::String, System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Set text and text properties of the artifact. |
| [SetValue](../artifact/setvalue/)(System::String, System::String) | Sets custom value of artifact. |
## See Also

* Class [Artifact](../artifact/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
