---
title: "PageAddTextHeader"
second_title: "Aspose.PDF för Go via C++"
description: "Lägg till text i sidhuvud."
type: docs
url: /sv/go-cpp/organize/pageaddtextheader/
---

_Lägg till text i sidhuvudet._

```go
func (document *Document) PageAddTextHeader(num int32, header string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **header** - pages header

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
	// PageAddTextHeader(num int32, header string) lägger till text i sidhuvudet
	err = pdf.PageAddTextHeader(1, "Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_PageAddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
