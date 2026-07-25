---
title: "ExportXfdf"
second_title: "Aspose.PDF para Go via C++"
description: "Exportar do documento PDF aberto anteriormente com AcroForm para documento XFDF."
type: docs
url: /pt/go-cpp/convert/exportxfdf/
---

_Exporta do PDF-documento previamente aberto com AcroForm para XFDF-document._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// ExportXfdf(filename string) exporta do PDF-documento previamente aberto com AcroForm para XFDF-document com filename
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
