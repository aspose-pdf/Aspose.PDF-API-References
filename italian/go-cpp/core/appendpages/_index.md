---
title: "AppendPages"
second_title: "Aspose.PDF per Go via C++"
description: "Aggiungi le pagine selezionate da un altro documento PDF."
type: docs
url: /it/go-cpp/core/appendpages/
---

_Aggiunge le pagine selezionate da un altro documento PDF._

```go
func (document *Document) AppendPages(anotherdocument *Document, pagerange string) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance
  * **pagerange** - string that specifies which pages to append. Supports individual pages, ranges, and open-ended intervals. For example: "1,3,5", "2-4", "-3", "4-", or "-" for all pages

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// Open(filename string) apre un altro PDF-document con il nome file
	anotherpdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer anotherpdf.Close()
	// AppendPages(anotherdocument *Document, pagerange string) aggiunge pagine specifiche da un altro documento PDF.
	err = pdf.AppendPages(anotherpdf, "1,3")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_AppendPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
