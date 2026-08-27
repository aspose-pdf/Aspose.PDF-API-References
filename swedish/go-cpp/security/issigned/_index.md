---
title: "IsSigned"
second_title: "Aspose.PDF för Go via C++"
description: "Hämta signeringsstatus för PDF-dokument."
type: docs
url: /sv/go-cpp/security/issigned/
---

_Hämta signeringsstatus för PDF-dokument._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// IsSigned() hämtar signeringsstatus för PDF-dokument
	isSig, _ := pdf.IsSigned()
	if isSig {
		fmt.Println("IsSigned() is true")
	}
}
```
