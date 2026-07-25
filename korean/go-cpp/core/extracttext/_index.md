---
title: "ExtractText"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF 문서 내용을 일반 텍스트로 반환합니다."
type: docs
url: /ko/go-cpp/core/extracttext/
---

_PDF 문서의 내용을 일반 텍스트로 반환합니다._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// ExtractText()는 PDF 문서의 내용을 일반 텍스트로 반환합니다
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// 인쇄
	fmt.Println("Extracted text:\n", txt)
}
```
