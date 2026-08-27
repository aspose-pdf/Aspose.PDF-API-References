---
title: "ExportFdf"
second_title: "Aspose.PDF para Go vía C++"
description: "Exportar del PDF-documento previamente abierto con AcroForm a documento FDF."
type: docs
url: /es/go-cpp/convert/exportfdf/
---

_Exportar del PDF abierto previamente con AcroForm a documento FDF._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// ExportFdf(filename string) exporta del PDF abierto previamente con AcroForm a documento FDF con el nombre de archivo
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
