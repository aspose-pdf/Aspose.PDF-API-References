---
title: "PageReplaceText"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "페이지의 텍스트를 교체합니다."
type: docs
url: /ko/go-cpp/organize/pagereplacetext/
---

_페이지의 텍스트를 교체합니다._

```go
func (document *Document) PageReplaceText(num int32, findText, replaceText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **findText** - text fragment to search
  * **replaceText** - text fragment to replace

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
	// PageReplaceText(num int32, findText, replaceText string)는 페이지의 텍스트를 교체합니다
	err = pdf.PageReplaceText(1, "PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string)는 이전에 연 PDF-document를 새 파일 이름으로 저장합니다
	err = pdf.SaveAs("sample_page1_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
