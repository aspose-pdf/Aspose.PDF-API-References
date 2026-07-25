---
title: "Rotate"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document를 회전합니다."
type: docs
url: /ko/go-cpp/organize/rotate/
---

_PDF 문서를 회전합니다._

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
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// Rotate(rotation int32) 은 PDF 문서를 회전합니다
	err = pdf.Rotate(asposepdf.RotationOn270)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_Rotate.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
