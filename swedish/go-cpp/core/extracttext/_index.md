---
title: "ExtractText"
second_title: "Aspose.PDF för Go via C++"
description: "Returnera PDF-dokumentets innehåll som vanlig text."
type: docs
url: /sv/go-cpp/core/extracttext/
---

_Returnera PDF-dokumentets innehåll som ren text._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// ExtractText() returnerar PDF-dokumentets innehåll som ren text
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Skriv ut
	fmt.Println("Extracted text:\n", txt)
}
```
