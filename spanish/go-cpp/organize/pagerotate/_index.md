---
title: "PageRotate"
second_title: "Aspose.PDF para Go vía C++"
description: "Rotar página."
type: docs
url: /es/go-cpp/organize/pagerotate/
---

_Rota la página._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// PageRotate(num int32, rotation int32) rota la página
	err = pdf.PageRotate(1, asposepdf.RotationOn180)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_page1_Rotate.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
