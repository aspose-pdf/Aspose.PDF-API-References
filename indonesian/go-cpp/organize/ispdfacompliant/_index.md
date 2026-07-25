---
title: "IsPdfaCompliant"
second_title: "Aspose.PDF untuk Go via C++"
description: "Dapatkan apakah PDF-document mematuhi PDF/A."
type: docs
url: /id/go-cpp/organize/ispdfacompliant/
---

_Get adalah PDF-document yang mematuhi PDF/A._

```go
func (document *Document) IsPdfaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/A compliant
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// IsPdfaCompliant() mendapatkan status kepatuhan PDF/A dari PDF-document
	isPdfa, _ := pdf.IsPdfaCompliant()
	if isPdfa {
		fmt.Println("IsPdfaCompliant() is true")
	} else {
		fmt.Println("IsPdfaCompliant() is false")
	}
}
```
