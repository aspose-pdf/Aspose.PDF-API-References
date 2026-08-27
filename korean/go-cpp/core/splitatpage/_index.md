---
title: "SplitAtPage"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF 문서를 두 개의 새 PDF 문서로 분할합니다."
type: docs
url: /ko/go-cpp/core/splitatpage/
---

_PDF-document를 두 개의 새 PDF-documents로 분할합니다._

```go
func SplitAtPage(document *Document, page int) (*Document, *Document, error)
```

**Parameters**: 
  * **document** - pointer to document
  * **page** - page number at which to split the PDF-document. Pages up to and including this page go into the first PDF-document

**Return**: 
  * **\*Document** - new PDF-document containing pages 1 to page (inclusive)
  * **\*Document** - new PDF-document containing pages from page + 1 to the end
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf_split.Close()

	// SplitAtPage(document *Document, page int) 은 두 개의 새 PDF-documents를 생성합니다
	left, right, err := asposepdf.SplitAtPage(pdf_split, 2)
	if err != nil {
		log.Fatal(err)
	}
	// Close()는 결과 PDF 문서에 할당된 리소스를 해제합니다
	defer left.Close()
	defer right.Close()

	// 각 부분을 별도의 파일로 저장합니다
	err = left.SaveAs("sample_SplitAtPage_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAtPage_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
