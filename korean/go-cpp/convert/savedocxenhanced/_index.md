---
title: "SaveDocXEnhanced"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "이전에 열었던 PDF-document를 향상된 인식 모드가 적용된 DocX-document로 변환하고 저장합니다(완전 편집 가능한 표와 단락)."
type: docs
url: /ko/go-cpp/convert/savedocxenhanced/
---

_이전에 연 PDF-document을 향상된 인식 모드(완전 편집 가능한 표와 단락)를 사용한 DocX-document로 변환하고 저장합니다._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
```

**Parameters**: 
  * **filename** - new filename

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
	// SaveDocX(filename string) 이전에 연 PDF-document을 filename을 사용하여 향상된 인식 모드 DocX-document로 저장합니다
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
