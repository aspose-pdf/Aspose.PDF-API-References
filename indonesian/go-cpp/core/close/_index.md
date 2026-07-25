---
title: "Close"
second_title: "Aspose.PDF untuk Go via C++"
description: "Lepaskan sumber daya yang dialokasikan untuk dokumen PDF."
type: docs
url: /id/go-cpp/core/close/
---

_Melepaskan sumber daya yang dialokasikan untuk PDF-document._

```go
func (document *Document) Close() error
```

**Parameters**: 

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New membuat PDF-document baru
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
