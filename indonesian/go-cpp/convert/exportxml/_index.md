---
title: "ExportXml"
second_title: "Aspose.PDF untuk Go via C++"
description: "Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XML-document."
type: docs
url: /id/go-cpp/convert/exportxml/
---

_Ekspor dari PDF-dokumen yang sebelumnya dibuka dengan AcroForm ke dokumen XML._

```go
func (document *Document) ExportXml(filename string) error
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
	// ExportXml(filename string) mengekspor dari PDF-dokumen yang sebelumnya dibuka dengan AcroForm ke dokumen XML dengan nama file
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
