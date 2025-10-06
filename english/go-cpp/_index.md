---
title: "Aspose.PDF for Go via C++"
description:  "Aspose.PDF for Go via C++"
keywords:  "Go, Golang, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /go-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Go via C++ allows developers manipulate them PDF files directly in the Go.

# Types

## Document
Document represents a PDF-document.

```go
type Document struct {
}
```

# Functions

## Convert from PDF functions

| Function | Description |
| -------- | ----------- |
| [SaveDocX](./convert/savedocx/) | Convert and save the previously opened PDF-document as DocX-document. |
| [SaveDoc](./convert/savedoc/) | Convert and save the previously opened PDF-document as Doc-document. |
| [SaveXlsX](./convert/savexlsx/) | Convert and save the previously opened PDF-document as XlsX-document. |
| [SaveTxt](./convert/savetxt/) | Convert and save the previously opened PDF-document as Txt-document. |
| [SavePptX](./convert/savepptx/) | Convert and save the previously opened PDF-document as PptX-document. |
| [SaveXps](./convert/savexps/) | Convert and save the previously opened PDF-document as Xps-document. |
| [SaveTeX](./convert/savetex/) | Convert and save the previously opened PDF-document as TeX-document. |
| [SaveEpub](./convert/saveepub/) | Convert and save the previously opened PDF-document as Epub-document. |
| [SaveBooklet](./convert/savebooklet/) | Convert and save the previously opened PDF-document as booklet PDF-document. |
| [SaveNUp](./convert/savenup/) | Convert and save the previously opened PDF-document as N-Up PDF-document. |
| [SaveMarkdown](./convert/savemarkdown/) | Convert and save the previously opened PDF-document as Markdown-document. |
| [SaveTiff](./convert/savetiff/) | Convert and save the previously opened PDF-document as Tiff-document. |
| [SaveDocXEnhanced](./convert/savedocxenhanced/) | Convert and save the previously opened PDF-document as DocX-document with Enhanced Recognition Mode (fully editable tables and paragraphs). |
| [SaveSvgZip](./convert/savesvgzip/) | Convert and save the previously opened PDF-document as SVG-archive. |
| [ExportFdf](./convert/exportfdf/) | Export from the previously opened PDF-document with AcroForm to FDF-document. |
| [ExportXfdf](./convert/exportxfdf/) | Export from the previously opened PDF-document with AcroForm to XFDF-document. |
| [ExportXml](./convert/exportxml/) | Export from the previously opened PDF-document with AcroForm to XML-document. |
| [PageToJpg](./convert/pagetojpg/) | Convert and save the specified page as Jpg-image. |
| [PageToPng](./convert/pagetopng/) | Convert and save the specified page as Png-image. |
| [PageToBmp](./convert/pagetobmp/) | Convert and save the specified page as Bmp-image. |
| [PageToTiff](./convert/pagetotiff/) | Convert and save the specified page as Tiff-image. |
| [PageToSvg](./convert/pagetosvg/) | Convert and save the specified page as Svg-image. |
| [PageToPdf](./convert/pagetopdf/) | Convert and save the specified page as Pdf. |
| [PageToDICOM](./convert/pagetodicom/) | Convert and save the specified page as DICOM-image. |


## Organize PDF functions

| Function | Description |
| -------- | ----------- |
| [Optimize](./organize/optimize/) | Optimize PDF-document content. |
| [OptimizeResource](./organize/optimizeresource/) | Optimize resources of PDF-document. |
| [Grayscale](./organize/grayscale/) | Convert PDF-document to black and white. |
| [Rotate](./organize/rotate/) | Rotate PDF-document. |
| [SetBackground](./organize/setbackground/) | Set PDF-document background color. |
| [Repair](./organize/repair/) | Repaire PDF-document. |
| [ReplaceText](./organize/replacetext/) | Replace text in PDF-document. |
| [AddPageNum](./organize/addpagenum/) | Add page number to a PDF-document. |
| [AddTextHeader](./organize/addtextheader/) | Add text in Header of a PDF-document. |
| [AddTextFooter](./organize/addtextfooter/) | Add text in Footer of a PDF-document. |
| [Flatten](./organize/flatten/) | Flatten PDF-document. |
| [RemoveAnnotations](./organize/removeannotations/) | Remove annotations from PDF-document. |
| [RemoveAttachments](./organize/removeattachments/) | Remove attachments from PDF-document. |
| [RemoveBlankPages](./organize/removeblankpages/) | Remove blank pages from PDF-document. |
| [RemoveBookmarks](./organize/removebookmarks/) | Remove bookmarks from PDF-document. |
| [RemoveHiddenText](./organize/removehiddentext/) | Remove hidden text from PDF-document. |
| [RemoveImages](./organize/removeimages/) | Remove images from PDF-document. |
| [RemoveJavaScripts](./organize/removejavascripts/) | Remove java scripts from PDF-document. |
| [RemoveTables](./organize/removetables/) | Remove tables from PDF-document. |
| [PageRotate](./organize/pagerotate/) | Rotate page. |
| [PageSetSize](./organize/pagesetsize/) | Set size of page. |
| [PageGrayscale](./organize/pagegrayscale/) | Convert page to black and white. |
| [PageAddText](./organize/pageaddtext/) | Add text on page. |
| [PageReplaceText](./organize/pagereplacetext/) | Replace text on page. |
| [PageAddPageNum](./organize/pageaddpagenum/) | Add page number on page. |
| [PageAddTextHeader](./organize/pageaddtextheader/) | Add text in page header. |
| [PageAddTextFooter](./organize/pageaddtextfooter/) | Add text in page footer. |
| [PageRemoveAnnotations](./organize/pageremoveannotations/) | Remove annotations in page. |
| [PageRemoveHiddenText](./organize/pageremovehiddentext/) | Remove hidden text in page. |
| [PageRemoveImages](./organize/pageremoveimages/) | Remove images in page. |
| [PageRemoveTables](./organize/pageremovetables/) | Remove tables in page. |


## Core PDF functions

| Function | Description |
| -------- | ----------- |
| [New](./core/new/) | Create a new PDF-document. |
| [Open](./core/open/) | Open a PDF-document with filename. |
| [Save](./core/save/) | Save the previously opened PDF-document. |
| [SaveAs](./core/saveas/) | Save the previously opened PDF-document with new filename. |
| [Close](./core/close/) | Release allocated resources for PDF-document. |
| [SetLicense](./core/setlicense/) | Set license with filename. |
| [ExtractText](./core/extracttext/) | Return the PDF-document contents as plain text. |
| [WordCount](./core/wordcount/) | Return word count in PDF-document. |
| [CharacterCount](./core/charactercount/) | Return character count in PDF-document. |
| [Append](./core/append/) | Append pages from another PDF-document. |
| [AppendPages](./core/appendpages/) | Append selected pages from another PDF-document. |
| [MergeDocuments](./core/mergedocuments/) | Create a new PDF-document by merging the provided PDF-documents. |
| [SplitDocument](./core/splitdocument/) | Create multiple new PDF-documents by extracting pages from the source PDF-document. |
| [SplitAtPage](./core/splitatpage/) | Split the PDF-document into two new PDF-documents. |
| [Bytes](./core/bytes/) | Return the contents of the PDF-document as a byte slice. |
| [PageAdd](./core/pageadd/) | Add new page in PDF-document. |
| [PageInsert](./core/pageinsert/) | Insert new page at the specified position in PDF-document. |
| [PageDelete](./core/pagedelete/) | Delete specified page in PDF-document. |
| [PageCount](./core/pagecount/) | Return page count in PDF-document. |
| [PageWordCount](./core/pagewordcount/) | Return word count on specified page in PDF-document. |
| [PageCharacterCount](./core/pagecharactercount/) | Return character count on specified page in PDF-document. |
| [PageIsBlank](./core/pageisblank/) | Return page is blank in PDF-document. |


## Miscellaneous

| Function | Description |
| -------- | ----------- |
| [About](./miscellaneous/about/) | Return metadata information about the Aspose.PDF for Go via C++. |


# Types secondary

## ProductInfo contains metadata about the Aspose.PDF for Go via C++.
```go
type ProductInfo struct {
	Product     string `json:"product"`     // Name
	Family      string `json:"family"`      // Family (e.g., "Aspose.PDF")
	Version     string `json:"version"`     // Version
	ReleaseDate string `json:"releasedate"` // Release date in ISO format (YYYY-MM-DD)
	Producer    string `json:"producer"`    // Producer
	IsLicensed  bool   `json:"islicensed"`  // License status (true if licensed)
}
```


# Constants

## Enumeration of possible rotation values.
```go
const (
    RotationNone  int32 = 0 // Non-rotated.
    RotationOn90  int32 = 1 // Rotated on 90 degrees clockwise.
    RotationOn180 int32 = 2 // Rotated on 180 degrees.
    RotationOn270 int32 = 3 // Rotated on 270 degrees clockwise.
    RotationOn360 int32 = 4 // Rotated on 360 degrees clockwise.
)
```

## Enumeration of possible page size values.
```go
const (
    PageSizeA0         int32 = 0  // A0 size.
    PageSizeA1         int32 = 1  // A1 size.
    PageSizeA2         int32 = 2  // A2 size.
    PageSizeA3         int32 = 3  // A3 size.
    PageSizeA4         int32 = 4  // A4 size.
    PageSizeA5         int32 = 5  // A5 size.
    PageSizeA6         int32 = 6  // A6 size.
    PageSizeB5         int32 = 7  // B5 size.
    PageSizePageLetter int32 = 8  // PageLetter size.
    PageSizePageLegal  int32 = 9  // PageLegal size.
    PageSizePageLedger int32 = 10 // PageLedger size.
    PageSizeP11x17     int32 = 11 // P11x17 size.
)
```
