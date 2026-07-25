---
title: "ExportXml"
second_title: "Aspose.PDF para Go via C++"
description: "Exportar do documento PDF aberto anteriormente com AcroForm para documento XML."
type: docs
url: /pt/go-cpp/convert/exportxml/
---

_Exporte do documento PDF previamente aberto com AcroForm para documento XML._

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
	// Open(filename string) abre um documento PDF com o nome de arquivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera os recursos alocados para o documento PDF
	defer pdf.Close()
	// ExportXml(filename string) exporta do documento PDF previamente aberto com AcroForm para documento XML com o nome de arquivo
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
