---
title: "PageAddStamp"
second_title: Aspose.PDF for Go via C++
description: "Add stamp on page."
type: docs
url: /go-cpp/organize/pageaddstamp/
---

_Add stamp on page._

```go
func (document *Document) PageAddStamp(num int32, alternativeText string, imageData []byte, isBackground bool, xIndent int32, yIndent int32, height int32, width int32, rotation int32, opacity float64) error
```

**Parameters**: 
  * **num** - the page number of the PDF-document
  * **alternativeText** - the alternative stamp text
  * **imageData** - the raw bytes of the image
  * **isBackground** - the stamp is background
  * **xIndent** - the x indent of the stamp
  * **yIndent** - the y indent of the stamp
  * **height** - the height of the stamp
  * **width** - the width of the stamp
  * **rotation** - the stamp rotation:
```go
const (
    RotationNone  int32 = 0 // Non-rotated.
    RotationOn90  int32 = 1 // Rotated on 90 degrees clockwise.
    RotationOn180 int32 = 2 // Rotated on 180 degrees.
    RotationOn270 int32 = 3 // Rotated on 270 degrees clockwise.
    RotationOn360 int32 = 4 // Rotated on 360 degrees clockwise.
)
```
  * **opacity** - the opacity (decimal)

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
	"os"
)

func main() {
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()

	// Load stamp image data
	imageBytes, err := os.ReadFile("stamp.png")
	if err != nil {
		log.Fatal(err)
	}

	// PageAddStamp adds stamp on page.
	err = pdf.PageAddStamp(1, "PageStamp", imageBytes, true, 100, 100, 50, 50, asposepdf.RotationOn90, 0.5)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_PageAddStamp.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
