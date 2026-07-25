---
title: "SaveXps"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "이전에 열었던 PDF-document를 Xps-document로 변환하고 저장합니다."
type: docs
url: /ko/go-cpp/convert/savexps/
---

_이전에 연 PDF-document을 Xps-document로 변환하고 저장합니다._

```go
func (document *Document) SaveXps(filename string) error
```

**Parameters**: 
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
	// SaveXps(filename string) 이전에 연 PDF-document을 filename을 사용하여 Xps-document로 저장합니다
	err = pdf.SaveXps("sample.xps")
	if err != nil {
		log.Fatal(err)
	}
}
```
