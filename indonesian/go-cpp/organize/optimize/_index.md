---
title: "Optimize"
second_title: "Aspose.PDF untuk Go via C++"
description: "Optimalkan konten PDF-document."
type: docs
url: /id/go-cpp/organize/optimize/
---

_Optimalkan konten PDF-document._

```go
func (document *Document) Optimize() error
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
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// Optimize() mengoptimalkan konten PDF-document
	err = pdf.Optimize()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_Optimize.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
