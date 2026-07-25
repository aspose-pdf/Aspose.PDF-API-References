---
title: "Aggiungi testo a piè di pagina"
second_title: "Aspose.PDF per Go via C++"
description: "Aggiungi testo nel piè di pagina di un documento PDF."
type: docs
url: /it/go-cpp/organize/addtextfooter/
---

_Aggiungi testo nel piè di pagina di un PDF-document._

```go
func (document *Document) AddTextFooter(footer string) error
```

**Parameters**: 
  * **footer** - pages footer

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
	// AddTextFooter(footer string) aggiunge testo nel piè di pagina di un PDF-document
	err = pdf.AddTextFooter("Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_AddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
