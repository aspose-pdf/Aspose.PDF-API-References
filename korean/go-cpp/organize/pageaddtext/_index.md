---
title: "PageAddText"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "페이지에 텍스트를 추가합니다."
type: docs
url: /ko/go-cpp/organize/pageaddtext/
---

_페이지에 텍스트를 추가합니다._

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string)는 페이지에 텍스트를 추가합니다
	err = pdf.PageAddText(1, "added text")
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
