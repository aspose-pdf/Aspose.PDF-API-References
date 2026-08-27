---
title: "PageAddText"
second_title: "Aspose.PDF per Go via C++"
description: "Aggiungi testo sulla pagina."
type: docs
url: /it/go-cpp/organize/pageaddtext/
---

_Aggiungi testo nella pagina._

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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageAddText(num int32, addText string) aggiunge testo nella pagina
	err = pdf.PageAddText(1, "added text")
	if err != nil {
		log.Fatal(err)
	}
	// Save() salva il PDF-document precedentemente aperto
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
