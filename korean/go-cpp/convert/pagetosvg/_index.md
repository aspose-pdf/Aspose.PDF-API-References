---
title: "PageToSvg"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "지정된 페이지를 Svg-image로 변환하고 저장합니다."
type: docs
url: /ko/go-cpp/convert/pagetosvg/
---

_지정된 페이지를 Svg-image로 변환하고 저장합니다._

```go
func (document *Document) PageToSvg(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **filename** - new filename

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
	// PageToSvg(num int32, filename string) 지정된 페이지를 Svg 이미지 파일로 저장합니다
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
