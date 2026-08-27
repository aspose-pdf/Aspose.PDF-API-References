---
title: "ExportXfdf"
second_title: "Aspose.PDF för Go via C++"
description: "Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till XFDF-dokument."
type: docs
url: /sv/go-cpp/convert/exportxfdf/
---

_Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till XFDF-dokument._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// ExportXfdf(filename string) exporterar från tidigare öppnat PDF-dokument med AcroForm till XFDF-dokument med filnamn
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
