---
title: "WordCount"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF 문서의 단어 수를 반환합니다."
type: docs
url: /ko/go-cpp/core/wordcount/
---

_PDF-document의 단어 수를 반환합니다._

```go
func (document *Document) WordCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - word count of the PDF-document
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
	// WordCount()는 PDF 문서의 단어 수를 반환합니다
	word_count, err := pdf.WordCount()
	if err != nil {
		log.Fatal(err)
	}
	// 인쇄
	fmt.Println("Word count:", word_count)
}
```
