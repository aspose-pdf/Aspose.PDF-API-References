---
title: "RemoveSigns"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document에서 서명을 제거합니다."
type: docs
url: /ko/go-cpp/security/removesigns/
---

_PDF-document에서 서명을 제거합니다._

```go
func (document *Document) RemoveSigns(filename string) error
```

**Parameters**: 
  * **filename** - new filename, without signs

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// RemoveSigns(filename string) 은 PDF-document에서 서명을 제거합니다
	err = pdf.RemoveSigns("sample_RemoveSigns.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
