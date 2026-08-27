---
title: "PageToPdf"
second_title: "Aspose.PDF för Go via C++"
description: "Konvertera och spara den angivna sidan som Pdf."
type: docs
url: /sv/go-cpp/convert/pagetopdf/
---

_Konvertera och spara den angivna sidan som PDF._

```go
func (document *Document) PageToPdf(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **filename** - new filename

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
	// PageToPdf(num int32, filename string) sparar den angivna sidan som PDF-fil
	err = pdf.PageToPdf(1, "sample_page1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
