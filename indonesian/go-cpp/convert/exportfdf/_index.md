---
title: "ExportFdf"
second_title: "Aspose.PDF untuk Go via C++"
description: "Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke FDF-document."
type: docs
url: /id/go-cpp/convert/exportfdf/
---

_Mengekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke FDF-document._

```go
func (document *Document) ExportFdf(filename string) error
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
	// ExportFdf(filename string) mengekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke FDF-document dengan nama file
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
