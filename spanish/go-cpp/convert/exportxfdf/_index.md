---
title: "ExportXfdf"
second_title: "Aspose.PDF para Go vía C++"
description: "Exportar del PDF-documento previamente abierto con AcroForm a documento XFDF."
type: docs
url: /es/go-cpp/convert/exportxfdf/
---

_Exporta del PDF-document previamente abierto con AcroForm a documento XFDF._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// ExportXfdf(filename string) exporta del PDF-document previamente abierto con AcroForm a documento XFDF con filename
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
