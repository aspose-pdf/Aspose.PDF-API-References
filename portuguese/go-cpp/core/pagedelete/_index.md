---
title: "PageDelete"
second_title: "Aspose.PDF para Go via C++"
description: "Exclua a página especificada no documento PDF."
type: docs
url: /pt/go-cpp/core/pagedelete/
---

_Exclui a página especificada no PDF-document._

```go
func (document *Document) PageDelete(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageDelete(num int32) exclui a página especificada no PDF-document
	err = pdf.PageDelete(1)
	if err != nil {
		log.Fatal(err)
	}
	// Save() salva o PDF-document aberto anteriormente
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
