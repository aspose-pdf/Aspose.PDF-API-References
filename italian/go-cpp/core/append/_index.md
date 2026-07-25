---
title: "Append"
second_title: "Aspose.PDF per Go via C++"
description: "Aggiungi pagine da un altro documento PDF."
type: docs
url: /it/go-cpp/core/append/
---

_Aggiunge pagine da un altro PDF-document._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

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

	// Open(filename string) apre un altro PDF-document con il nome file
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() rilascia le risorse allocate per il PDF-document
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) aggiunge pagine da un altro PDF-document.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
