---
title: "MergeDocuments"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "제공된 PDF 문서를 병합하여 새 PDF 문서를 생성합니다."
type: docs
url: /ko/go-cpp/core/mergedocuments/
---

_제공된 PDF 문서를 병합하여 새 PDF 문서를 생성합니다._

```go
func MergeDocuments(documents []*Document) (*Document, error)
```

**Parameters**: 
  * **documents** - slice of PDF-documents to be merged

**Return**: 
  * **\*Document** - new PDF-document containing all pages from the provided PDF-documents
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New는 새로운 PDF-document를 생성합니다
	pdf1, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf1.Close()
	err = pdf1.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf2, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf2.Close()
	// MergeDocuments(documents []*Document) 제공된 문서를 병합하여 새 PDF 문서를 생성합니다.
	pdf_merged, err := asposepdf.MergeDocuments([]*asposepdf.Document{pdf1, pdf2})
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf_merged.Close()
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf_merged.SaveAs("sample_MergeDocuments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
