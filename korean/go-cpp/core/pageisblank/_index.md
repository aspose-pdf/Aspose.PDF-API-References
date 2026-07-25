---
title: "PageIsBlank"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document의 페이지가 비어 있는지 반환합니다."
type: docs
url: /ko/go-cpp/core/pageisblank/
---

_PDF-document에서 페이지가 비어 있음을 반환합니다._

```go
func (document *Document) PageIsBlank(num int32) (bool, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **bool** - the page is blank
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
	// PageIsBlank(num int32) 은 PDF-document에서 페이지가 비어 있음을 반환합니다.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// 인쇄
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
