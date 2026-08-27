---
title: "PageInsert"
second_title: "Aspose.PDF para Go via C++"
description: "Insira uma nova página na posição especificada no documento PDF."
type: docs
url: /pt/go-cpp/core/pageinsert/
---

_Insere nova página na posição especificada no documento PDF._

```go
func (document *Document) PageInsert(num int32) error
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
	// PageInsert(num int32) insere nova página na posição especificada no documento PDF
	err = pdf.PageInsert(1)
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
