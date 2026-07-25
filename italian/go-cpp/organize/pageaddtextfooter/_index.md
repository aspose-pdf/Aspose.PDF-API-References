---
title: "PageAddTextFooter"
second_title: "Aspose.PDF per Go via C++"
description: "Aggiungi testo nel piè di pagina della pagina."
type: docs
url: /it/go-cpp/organize/pageaddtextfooter/
---

_Aggiungi testo nel piè di pagina della pagina._

```go
func (document *Document) PageAddTextFooter(num int32, footer string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageAddTextFooter(num int32, footer string) aggiunge testo nel piè di pagina della pagina
	err = pdf.PageAddTextFooter(1, "Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_PageAddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
