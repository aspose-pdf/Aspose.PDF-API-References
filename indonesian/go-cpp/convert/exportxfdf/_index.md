---
title: "ExportXfdf"
second_title: "Aspose.PDF untuk Go via C++"
description: "Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XFDF-document."
type: docs
url: /id/go-cpp/convert/exportxfdf/
---

_Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XFDF-document._

```go
func (document *Document) ExportXfdf(filename string) error
```

**Parameters**: 
  * **filename** - new filename

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
	// ExportXfdf(filename string) mengekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XFDF-document dengan nama file
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
