---
title: "Append"
second_title: "Aspose.PDF för Go via C++"
description: "Lägg till sidor från ett annat PDF-dokument."
type: docs
url: /sv/go-cpp/core/append/
---

_Lägger till sidor från ett annat PDF-dokument._

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

	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()

	// Open(filename string) öppnar ett annat PDF-dokument med filnamnet
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() frigör allokerade resurser för PDF-dokument
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) lägger till sidor från ett annat PDF-dokument.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
