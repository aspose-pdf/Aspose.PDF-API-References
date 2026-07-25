---
title: "PageWordCount"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document의 지정된 페이지에 대한 단어 수를 반환합니다."
type: docs
url: /ko/go-cpp/core/pagewordcount/
---

_PDF 문서의 지정된 페이지에서 단어 수를 반환합니다._

```go
func (document *Document) PageWordCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - word count on the page
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
	// PageWordCount(num int32) 지정된 페이지에서 단어 수를 반환합니다.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// 인쇄
	fmt.Println("Word count on the first page:", page_word_count)
}
```
