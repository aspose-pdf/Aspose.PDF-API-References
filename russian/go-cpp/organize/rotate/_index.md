---
title: "Rotate"
second_title: "Aspose.PDF для Go через C++"
description: "Повернуть PDF-документ."
type: docs
url: /ru/go-cpp/organize/rotate/
---

_Повернуть PDF-документ._

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
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// Rotate(rotation int32) поворачивает PDF-документ
	err = pdf.Rotate(asposepdf.RotationOn270)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_Rotate.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
