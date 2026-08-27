---
title: "IsLinearized"
second_title: "Aspose.PDF untuk Go via C++"
description: "Dapatkan nilai yang menunjukkan apakah dokumen terlinier."
type: docs
url: /id/go-cpp/core/islinearized/
---

_Dapatkan nilai yang menunjukkan apakah dokumen terlinier._

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
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// IsLinearized() mendapatkan nilai yang menunjukkan apakah dokumen terlinier
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
