---
title: "PageAddText"
second_title: "Aspose.PDF para Go via C++"
description: "Adicionar texto na página."
type: docs
url: /pt/go-cpp/organize/pageaddtext/
---

_Adicionar texto na página._

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string) adiciona texto na página
	err = pdf.PageAddText(1, "added text")
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
