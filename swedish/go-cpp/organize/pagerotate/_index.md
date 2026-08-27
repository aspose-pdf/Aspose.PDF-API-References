---
title: "PageRotate"
second_title: "Aspose.PDF för Go via C++"
description: "Rotera sida."
type: docs
url: /sv/go-cpp/organize/pagerotate/
---

_Rotera sidan._

```go
func (document *Document) PageRotate(num int32, rotation int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **rotation** - page rotation:
```go
const (
    RotationNone  int32 = 0 // Non-rotated.
    RotationOn90  int32 = 1 // Rotated on 90 degrees clockwise.
    RotationOn180 int32 = 2 // Rotated on 180 degrees.
    RotationOn270 int32 = 3 // Rotated on 270 degrees clockwise.
    RotationOn360 int32 = 4 // Rotated on 360 degrees clockwise.
)
```

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// PageRotate(num int32, rotation int32) roterar sidan
	err = pdf.PageRotate(1, asposepdf.RotationOn180)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_page1_Rotate.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
