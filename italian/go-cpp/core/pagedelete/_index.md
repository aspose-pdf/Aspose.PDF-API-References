---
title: "PageDelete"
second_title: "Aspose.PDF per Go via C++"
description: "Elimina la pagina specificata nel documento PDF."
type: docs
url: /it/go-cpp/core/pagedelete/
---

_Elimina la pagina specificata nel PDF-document._

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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageDelete(num int32) elimina la pagina specificata nel PDF-document
	err = pdf.PageDelete(1)
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
