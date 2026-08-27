---
title: "AddTextHeader"
second_title: "Aspose.PDF för Go via C++"
description: "Lägg till text i rubriken på ett PDF-dokument."
type: docs
url: /sv/go-cpp/organize/addtextheader/
---

_Lägg till text i rubriken på ett PDF-dokument._

```go
func (document *Document) AddTextHeader(header string) error
```

**Parameters**: 
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
	// AddTextHeader(header string) lägger till text i rubriken på ett PDF-dokument
	err = pdf.AddTextHeader("Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_AddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
