---
title: Aspose::Pdf::Page class
linktitle: Page
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Page class. Class representing page of PDF document in C++.'
type: docs
weight: 13200
url: /cpp/aspose.pdf/page/
---
## Page class


Class representing page of PDF document.

```cpp
class Page : public System::IDisposable,
             public Aspose::Pdf::ISupportsMemoryCleanup,
             public Aspose::Pdf::IOperatorContainer
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Annotations::AnnotationSelector\>\&) | Accepts [AnnotationSelector](../) visitor object that provides functionality to work with annotations. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Text::TextFragmentAbsorber\>\&) | Accepts **TextFragmentAbsorber** visitor object that provides functionality to work with text objects. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::ImagePlacementAbsorber\>\&) | Accepts [ImagePlacementAbsorber](../imageplacementabsorber/) visitor object that provides functionality to work with image placement objects. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Text::TextAbsorber\>\&) | Accepts **TextAbsorber** visitor object that provides functionality to work with text objects. |
| [AddGraphics](./addgraphics/)(System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>, System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Adds graphics to the page. Works faster than adding elements one by one with [GraphicElement::AddOnPage(Page)](../) method. |
| [AddImage](./addimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Pdf::Rectangle\>, System::SharedPtr\<Aspose::Pdf::Rectangle\>, bool) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddImage](./addimage/)(System::String, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Pdf::Rectangle\>, System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddImage](./addimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Pdf::Rectangle\>, int32_t, int32_t, bool, System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Adds image on page and places it depend on image rectangle position. |
| [AddImage](./addimage/)(System::String, System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddStamp](./addstamp/)(System::SharedPtr\<Aspose::Pdf::Stamp\>) | Put stamp into page. [Stamp](../stamp/) can be page number, image or simple text, e.g. some logo. |
| [AsByteArray](./asbytearray/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Converts current page as bitmap and than returns array of bytes. |
| [AsXml](./asxml/)() | Converts current page as xml in utf8 encoding. |
| [CalculateContentBBox](./calculatecontentbbox/)() | Calculates bbox value - rectangle containing contents without visible margins. |
| [ConvertToPNGMemoryStream](./converttopngmemorystream/)() | Convert page to PNG for DSR, OMR, OCR image stream. |
| [DeleteGraphics](./deletegraphics/)(System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>) | Deletes graphics from the page. Works faster than deleting elements one by one with [GraphicElement::Remove](../) method. |
| [Dispose](./dispose/)() override | Frees up memory. |
| [Flatten](./flatten/)() | Removes all fields located on the page and place their values instead. |
| [FreeMemory](./freememory/)() override | Clears cached data. |
| [get_Actions](./get_actions/)() | Gets collection of page properties. |
| [get_Annotations](./get_annotations/)() | Gets collection of page annotations. [Annotations](../../aspose.pdf.annotations/) |
| [get_ArtBox](./get_artbox/)() | Gets art box of the page. |
| [get_Artifacts](./get_artifacts/)() | Gets collection of artifacts on the page. |
| [get_Background](./get_background/)() | Gets the background color of the page. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Gets background image for page (for generator only, not filled in when reading document). |
| [get_BleedBox](./get_bleedbox/)() | Gets bleed box of the page. |
| [get_ColorType](./get_colortype/)() | Sets color type of the pages based on information getting from operators SetColor, images and forms. |
| [get_Contents](./get_contents/)() override | Gets collection of operators in the content stream of the page. [OperatorCollection](../operatorcollection/) |
| [get_CropBox](./get_cropbox/)() | Gets crop box of the page. |
| [get_Duration](./get_duration/)() | Gets of set page display duration. This is time in seconds that page shall be displayed during presentation. Returns -1 if duration is not defined. |
| [get_FieldsInTabOrder](./get_fieldsintaborder/)() | Gets list of Field object in Tab order on this page. |
| [get_Footer](./get_footer/)() const | Gets page footer. |
| [get_Group](./get_group/)() | Gets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model. |
| [get_Header](./get_header/)() const | Gets page header. |
| [get_IsAddParagraphsAfterLast](./get_isaddparagraphsafterlast/)() const | Gets the addition of paragraphs after the last paragraph of the page. |
| [get_Layers](./get_layers/)() | Gets layers collection. |
| [get_MediaBox](./get_mediabox/)() | Gets media box of the page. |
| [get_NoteLineStyle](./get_notelinestyle/)() | Gets the line style for notes.(for generator only, not filled in when reading document) |
| [get_Number](./get_number/)() | Get number of the page. |
| [get_PageInfo](./get_pageinfo/)() | Gets the page info (for generator only, not filled in when reading document). |
| [get_Paragraphs](./get_paragraphs/)() | Gets the paragraphs. |
| [get_Rect](./get_rect/)() | Gets rectangle of the page. For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect. |
| [get_Resources](./get_resources/)() override | Gets page resources. [Resources](../resources/) object contains collections of images, forms and fonts. [Resources](../resources/) |
| [get_Rotate](./get_rotate/)() | Gets rotation of the page. |
| [get_RotationMatrix](./get_rotationmatrix/)() | Gets transofmation matrix for the page. |
| [get_TabOrder](./get_taborder/)() | Gets tab order of the page. Possible values: [Row](../row/), Column. Default, Manual. |
| [get_TocInfo](./get_tocinfo/)() const | Gets table of contents info. |
| [get_TrimBox](./get_trimbox/)() | Gets trim box of the page. |
| [get_UserUnit](./get_userunit/)() | Gets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 / 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page. |
| [get_Watermark](./get_watermark/)() | Gets the watermark of the page. |
| [GetNotifications](./getnotifications/)() | Returns notifications about inside operations with page content. (Only notifications about paragraph events in text adding scenarios are supported now.) |
| [GetPageRect](./getpagerect/)(bool) | Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null). |
| [GetResources](./getresources/)() override | Retrieves the resources associated with the page. |
| [HasVectorGraphics](./hasvectorgraphics/)() | Detect of the presence of vector graphics, if it is present on the page. |
| static [IntToRotation](./inttorotation/)(int32_t) | Translates integer value into corresponding rotation enumeration member. |
| [IsBlank](./isblank/)(double) | Gets the flag whether page is blank or not. |
| [MakeGrayscale](./makegrayscale/)() | Converts the page to grayscale. |
| [MergeLayers](./mergelayers/)(System::String) | Merges all layers on the page into a single layer with the specified new layer name. |
| [MergeLayers](./mergelayers/)(System::String, System::String) | Merges all layers on the page into a single layer with the specified new layer name and optional content group [Id](../id/). |
| [Resize](./resize/)(System::SharedPtr\<Aspose::Pdf::PageSize\>) | Resizes the page. |
| static [RotationToInt](./rotationtoint/)(Aspose::Pdf::Rotation) | Translates rotation enumeration member into integer value. |
| [SendTo](./sendto/)(System::SharedPtr\<Aspose::Pdf::Devices::PageDevice\>, System::SharedPtr\<System::IO::Stream\>) | Sends page to process with given page device. |
| [SendTo](./sendto/)(System::SharedPtr\<Aspose::Pdf::Devices::PageDevice\>, System::String) | Sends page to process with given page device. |
| [set_ArtBox](./set_artbox/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets art box of the page. |
| [set_Background](./set_background/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets the background color of the page. |
| [set_BackgroundImage](./set_backgroundimage/)(System::SharedPtr\<Aspose::Pdf::Image\>) | Sets background image for page (for generator only, not filled in when reading document). |
| [set_BleedBox](./set_bleedbox/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets bleed box of the page. |
| [set_CropBox](./set_cropbox/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets crop box of the page. |
| [set_Duration](./set_duration/)(double) | Gets of set page display duration. This is time in seconds that page shall be displayed during presentation. Returns -1 if duration is not defined. |
| [set_Footer](./set_footer/)(System::SharedPtr\<Aspose::Pdf::HeaderFooter\>) | Sets page footer. |
| [set_Group](./set_group/)(System::SharedPtr\<Aspose::Pdf::Group\>) | Sets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model. |
| [set_Header](./set_header/)(System::SharedPtr\<Aspose::Pdf::HeaderFooter\>) | Sets page header. |
| [set_IsAddParagraphsAfterLast](./set_isaddparagraphsafterlast/)(bool) | Sets the addition of paragraphs after the last paragraph of the page. |
| [set_Layers](./set_layers/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Layer\>\>\>) | Sets layers collection. |
| [set_MediaBox](./set_mediabox/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets media box of the page. |
| [set_NoteLineStyle](./set_notelinestyle/)(System::SharedPtr\<Aspose::Pdf::GraphInfo\>) | Sets the line style for notes.(for generator only, not filled in when reading document) |
| [set_PageInfo](./set_pageinfo/)(System::SharedPtr\<Aspose::Pdf::PageInfo\>) | Sets the page info (for generator only, not filled in when reading document). |
| [set_Paragraphs](./set_paragraphs/)(System::SharedPtr\<Aspose::Pdf::Paragraphs\>) | Gets the paragraphs. |
| [set_Rect](./set_rect/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets rectangle of the page. For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect. |
| [set_Rotate](./set_rotate/)(Aspose::Pdf::Rotation) | Sets rotation of the page. |
| [set_TabOrder](./set_taborder/)(Aspose::Pdf::TabOrder) | Sets tab order of the page. Possible values: [Row](../row/), Column. Default, Manual. |
| [set_TocInfo](./set_tocinfo/)(System::SharedPtr\<Aspose::Pdf::TocInfo\>) | Sets table of contents info. |
| [set_TrimBox](./set_trimbox/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets trim box of the page. |
| [set_UserUnit](./set_userunit/)(double) | Sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 / 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page. |
| [set_Watermark](./set_watermark/)(System::SharedPtr\<Aspose::Pdf::Watermark\>) | Sets the watermark of the page. |
| [SetPageSize](./setpagesize/)(double, double) | Sets page size for page. |
| [TrySaveVectorGraphics](./trysavevectorgraphics/)(System::String) | Tries to save vector graphics if they are present on the page. The save format is SVG. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BeforePageGenerate](./beforepagegenerate/) | Procedure for customize header and footer. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Class [IOperatorContainer](../ioperatorcontainer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
