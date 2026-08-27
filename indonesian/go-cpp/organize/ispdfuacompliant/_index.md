---
title: "IsPdfUaCompliant"
second_title: "Aspose.PDF untuk Go via C++"
description: "Dapatkan apakah PDF-document mematuhi PDF/UA."
type: docs
url: /id/go-cpp/organize/ispdfuacompliant/
---

_Dapatkan apakah dokumen PDF mematuhi PDF/UA._

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
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// IsPdfUaCompliant() mendapatkan status kepatuhan PDF/UA dari dokumen PDF
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
