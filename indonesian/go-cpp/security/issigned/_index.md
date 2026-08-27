---
title: "IsSigned"
second_title: "Aspose.PDF untuk Go via C++"
description: "Dapatkan status tertandatangani dari PDF-dokumen."
type: docs
url: /id/go-cpp/security/issigned/
---

_Dapatkan status penandatanganan dokumen PDF._

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
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// IsSigned() mendapatkan status penandatanganan dokumen PDF
	isSig, _ := pdf.IsSigned()
	if isSig {
		fmt.Println("IsSigned() is true")
	}
}
```
