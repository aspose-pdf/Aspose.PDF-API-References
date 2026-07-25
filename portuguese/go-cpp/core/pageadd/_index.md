---
title: "PageAdd"
second_title: "Aspose.PDF para Go via C++"
description: "Adicione uma nova página no documento PDF."
type: docs
url: /pt/go-cpp/core/pageadd/
---

_Adicionar nova página no PDF-document._

```go
func (document *Document) PageAdd() error
```

**Parameters**: 

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
	// PageAdd() adiciona nova página no PDF-document
	err = pdf.PageAdd()
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
