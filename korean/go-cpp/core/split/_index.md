---
title: "분할"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "현재 PDF 문서에서 페이지를 추출하여 여러 새 PDF 문서를 생성합니다."
type: docs
url: /ko/go-cpp/core/split/
---

_현재 PDF 문서에서 페이지를 추출하여 여러 개의 새 PDF 문서를 생성합니다._

```go
func (document *Document) Split(pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
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

	// Split(pagerange string) 현재 PDF 문서에서 페이지를 추출하여 여러 개의 새 PDF 문서를 생성합니다
	pdfs, err := pdf_split.Split("1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// 분할된 각 PDF 문서를 별도의 파일로 저장합니다
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_Split_part%d.pdf", i+1)
		// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
