---
title: "ExportFdf"
second_title: "Aspose.PDF para Go via C++"
description: "Exportar do documento PDF aberto anteriormente com AcroForm para documento FDF."
type: docs
url: /pt/go-cpp/convert/exportfdf/
---

_Exportar do PDF-document aberto anteriormente com AcroForm para FDF-document._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// ExportFdf(filename string) exporta do PDF-document aberto anteriormente com AcroForm para FDF-document com nome de arquivo
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
