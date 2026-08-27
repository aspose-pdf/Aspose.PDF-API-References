---
title: "SaveNUp"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "이전에 열었던 PDF-document를 N-Up PDF-document로 변환하고 저장합니다."
type: docs
url: /ko/go-cpp/convert/savenup/
---

_이전에 열려 있던 PDF 문서를 N-Up PDF 문서로 변환하고 저장합니다._

```go
func (document *Document) SaveNUp(filename string, columns int32, rows int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **columns** - number of columns
  * **rows** - number of rows

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
	// SaveNUp(filename string, columns int32, rows int32) 이전에 열려 있던 PDF 문서를 N-Up PDF 문서로 파일 이름과 함께 저장합니다
	err = pdf.SaveNUp("sample_NUp.pdf", 2, 2)
	if err != nil {
		log.Fatal(err)
	}
}
```
