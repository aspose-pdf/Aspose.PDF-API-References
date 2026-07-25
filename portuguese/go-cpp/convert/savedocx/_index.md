---
title: "SaveDocX"
second_title: "Aspose.PDF para Go via C++"
description: "Converter e salvar o documento PDF aberto anteriormente como documento DocX."
type: docs
url: /pt/go-cpp/convert/savedocx/
---

_Converter e salvar o PDF-document aberto anteriormente como DocX-document._

```go
func (document *Document) SaveDocX(filename string) error
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
	// SaveDocX(filename string) salva o PDF-document aberto anteriormente como DocX-document com nome de arquivo
	err = pdf.SaveDocX("sample.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
