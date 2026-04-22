---
title: "IsSigned"
second_title: Aspose.PDF for Go via C++
description: "Get signed status of PDF-document."
type: docs
url: /go-cpp/security/issigned/
---

_Get signed status of PDF-document._

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
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// IsSigned() gets signed status of PDF-document
	isSig, _ := pdf.IsSigned()
	if isSig {
		fmt.Println("IsSigned() is true")
	}
}
```
