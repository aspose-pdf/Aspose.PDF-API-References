---
title: "OptimizeResource"
second_title: "Aspose.PDF untuk Go via C++"
description: "Optimalkan sumber daya PDF-document."
type: docs
url: /id/go-cpp/organize/optimizeresource/
---

_Optimalkan sumber daya dokumen PDF._

```go
func (document *Document) OptimizeResource() error
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
	// OptimizeResource() mengoptimalkan sumber daya dokumen PDF
	err = pdf.OptimizeResource()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_OptimizeResource.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
