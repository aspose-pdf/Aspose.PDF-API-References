---
title: "PageInsert"
second_title: "Aspose.PDF per Go via C++"
description: "Inserisci una nuova pagina nella posizione specificata del documento PDF."
type: docs
url: /it/go-cpp/core/pageinsert/
---

_Inserisce una nuova pagina nella posizione specificata nel PDF-document._

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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageInsert(num int32) inserisce una nuova pagina nella posizione specificata nel PDF-document
	err = pdf.PageInsert(1)
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
