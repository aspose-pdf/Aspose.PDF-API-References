---
title: "PageAddTextFooter"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "페이지 푸터에 텍스트를 추가합니다."
type: docs
url: /ko/go-cpp/organize/pageaddtextfooter/
---

_페이지 하단에 텍스트를 추가합니다._

```go
func (document *Document) PageAddTextFooter(num int32, footer string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **footer** - pages footer

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
	// PageAddTextFooter(num int32, footer string) 은 페이지 하단에 텍스트를 추가합니다
	err = pdf.PageAddTextFooter(1, "Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_PageAddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
