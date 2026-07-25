---
title: "PageAdd"
second_title: "Aspose.PDF per Go via C++"
description: "Aggiungi una nuova pagina nel documento PDF."
type: docs
url: /it/go-cpp/core/pageadd/
---

_Aggiungi una nuova pagina nel documento PDF._

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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageAdd() aggiunge una nuova pagina nel documento PDF
	err = pdf.PageAdd()
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
