---
title: "Rotate"
second_title: "Aspose.PDF per Go via C++"
description: "Ruota il documento PDF."
type: docs
url: /it/go-cpp/organize/rotate/
---

_Ruota PDF-document._

```go
func (document *Document) Rotate(rotation int32) error
```

**Parameters**: 
  * **rotation** - pages rotation:
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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// Rotate(rotation int32) ruota PDF-document
	err = pdf.Rotate(asposepdf.RotationOn270)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_Rotate.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
