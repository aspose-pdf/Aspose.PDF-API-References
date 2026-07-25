---
title: "PageAdd"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document에 새 페이지를 추가합니다."
type: docs
url: /ko/go-cpp/core/pageadd/
---

_PDF 문서에 새 페이지를 추가합니다._

```go
func (document *Document) PageAdd() error
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
	// PageAdd() PDF 문서에 새 페이지를 추가합니다
	err = pdf.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Save()는 이전에 연 PDF-document를 저장합니다
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
