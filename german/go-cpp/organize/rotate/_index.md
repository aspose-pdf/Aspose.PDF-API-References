---
title: "Rotate"
second_title: "Aspose.PDF für Go über C++"
description: "PDF-Dokument drehen."
type: docs
url: /de/go-cpp/organize/rotate/
---

_Dreht das PDF-Dokument._

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
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// Rotate(rotation int32) dreht das PDF-Dokument
	err = pdf.Rotate(asposepdf.RotationOn270)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_Rotate.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
