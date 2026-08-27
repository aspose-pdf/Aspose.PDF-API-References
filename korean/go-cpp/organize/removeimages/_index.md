---
title: "RemoveImages"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document에서 이미지를 제거합니다."
type: docs
url: /ko/go-cpp/organize/removeimages/
---

_PDF-document에서 이미지를 제거합니다._

```go
func (document *Document) RemoveImages() error
```

**Parameters**: 

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
	// RemoveImages()는 PDF-document에서 이미지를 제거합니다
	err = pdf.RemoveImages()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_RemoveImages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
