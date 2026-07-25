---
title: "Open"
second_title: "Aspose.PDF untuk Go via C++"
description: "Buka dokumen PDF dengan nama file."
type: docs
url: /id/go-cpp/core/open/
---

_Buka PDF-document dengan nama file._

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// Save() menyimpan PDF-document yang sebelumnya dibuka
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
