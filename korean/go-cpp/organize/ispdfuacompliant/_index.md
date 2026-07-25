---
title: "IsPdfUaCompliant"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "PDF-document가 PDF/UA 준수인지 확인합니다."
type: docs
url: /ko/go-cpp/organize/ispdfuacompliant/
---

_PDF-document가 PDF/UA 규격을 준수하는지 확인합니다._

```go
func (document *Document) IsPdfUaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/UA compliant
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
	// IsPdfUaCompliant()는 PDF-document의 PDF/UA 준수 상태를 가져옵니다
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
