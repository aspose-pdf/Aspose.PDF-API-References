---
title: "ExtractText"
second_title: "Aspose.PDF per Go via C++"
description: "Restituisce il contenuto del documento PDF come testo semplice."
type: docs
url: /it/go-cpp/core/extracttext/
---

_Restituisci il contenuto del documento PDF come testo semplice._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// ExtractText() restituisce il contenuto del documento PDF come testo semplice
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Extracted text:\n", txt)
}
```
