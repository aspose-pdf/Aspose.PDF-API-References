---
title: "New"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "새 PDF 문서를 생성합니다."
type: docs
url: /ko/go-cpp/core/new/
---

_새 PDF 문서를 생성합니다._

```go
func New() (*Document, error)
```

**Parameters**: 

**Return**:
  * **\*Document** - pointer to document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New는 새로운 PDF-document를 생성합니다
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
