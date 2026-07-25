---
title: "IsSigned"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document의 서명 상태를 가져옵니다."
type: docs
url: /ko/go-cpp/security/issigned/
---

_PDF-document의 서명 상태를 가져옵니다._

```go
func (document *Document) IsSigned() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is signed
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()
	// IsSigned() 은 PDF-document의 서명 상태를 가져옵니다
	isSig, _ := pdf.IsSigned()
	if isSig {
		fmt.Println("IsSigned() is true")
	}
}
```
