---
title: "IsLinearized"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "문서가 선형화되었는지 여부를 나타내는 값을 가져옵니다."
type: docs
url: /ko/go-cpp/core/islinearized/
---

_문서가 선형화되었는지 여부를 나타내는 값을 가져옵니다._

```go
func (document *Document) IsLinearized() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is linearized
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
	// IsLinearized() 문서가 선형화되었는지 여부를 나타내는 값을 가져옵니다
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
