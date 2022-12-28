---
title: HeaderArtifact
second_title: Aspose.PDF for Python via .NET API Reference
description: Class describes Heaader artifact. This artifacgt may be used to set heading of the page.
type: docs
weight: 440
url: /python-net/aspose.pdf/headerartifact/
---

## HeaderArtifact class

Class describes Heaader artifact. This artifacgt may be used to set heading of the page.

The HeaderArtifact type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|HeaderArtifact()|Creates Header Artifact instance.|
## Properties
| Name | Description |
| :- | :- |
|custom_type|Gets name of artifact type. May be used if artifact type is non standard.|
|custom_subtype|Gets name of artifact subtype. May be used  if artifact subtype is not standard subtype.|
|type|Gets artifact type.|
|subtype|Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype.|
|contents|Gets collection of artifact internal operators.|
|form|Gets XForm of the artifact (if XForm is used).|
|rectangle|Gets rectangle of the artifact.|
|position|Gets or sets artifact position.<br/>            If this property is specified, then margins and alignments are ignored.|
|right_margin|Right margin of artifact. <br/>            If position is specified explicitly (in Position property) this value is ignored.|
|left_margin|Left margin of artifact. <br/>            If position is specified explicitly (in Position property) this value is ignored.|
|top_margin|Top margin of artifact. <br/>            If position is specified explicitly (in Position property) this value is ignored.|
|bottom_margin|Bottom margin of artifact. <br/>            If position is specified explicitly (in Position property) this value is ignored.|
|artifact_horizontal_alignment|Horizontal alignment of artifact. <br/>            If position is specified explicitly (in Position property) this value is ignored.|
|artifact_vertical_alignment|Vertical alignment of artifact. <br/>            If position is specified explicitly (in Position property) this value is ignored.|
|rotation|Gets or sets artifact rotation angle.|
|text|Gets text of the artifact.|
|image|Gets image of the artifact (if presents).|
|opacity|Gets or sets opacity of the artifact. Possible values are in range 0..1.|
|lines|Lines of multiline text artifact.|
|text_state|Text state for artifact text.|
|is_background|If true Artifact is placed behind page contents.|
## Methods
| Name | Description |
| :- | :- |
|set_image(image_stream)|Sets image of the artifact.|
|set_image(image_name)|Sets image of the artifact.|
|set_text(formatted_text)|Sets text of the artifact.|
|set_text_and_state(text, text_state)|Set text and text properties of the artifact.|
|set_lines_and_state(text, text_state)|Set text and text properties of the artifact. Allows to specify multiple lines.|
|set_pdf_page(page)|Sets PDF page which is placed on the document page as artifact.|
|get_value(name)|Gets custom value of artifact.|
|set_value(name, value)|Sets custom value of artifact.|
|remove_value(name)|Remove custom value from the artifact.|
|begin_updates()|Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. <br/>            Usually artifact operators are changed anytime when artifact property was changed. This causes changing of page contents<br/>            everytime when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls.<br/>            This allows to change page contents only once.|
|save_updates()|Saves all updates in artifact which were made after BeginUpdates() call.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

