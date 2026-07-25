---
title: "ExportXml"
second_title: "Aspose.PDF para Go vía C++"
description: "Exportar del PDF-documento previamente abierto con AcroForm a documento XML."
type: docs
url: /es/go-cpp/convert/exportxml/
---

_Exportar del PDF-documento previamente abierto con AcroForm a documento XML._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// ExportXml(filename string) exporta del PDF-documento previamente abierto con AcroForm a documento XML con el nombre de archivo
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
