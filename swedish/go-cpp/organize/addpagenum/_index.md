---
title: "AddPageNum"
second_title: "Aspose.PDF för Go via C++"
description: "Lägg till sidnummer i ett PDF-dokument."
type: docs
url: /sv/go-cpp/organize/addpagenum/
---

_Lägg till sidnummer i ett PDF-dokument._

```go
func (document *Document) AddPageNum() error
```

**Parameters**: 

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
	// AddPageNum() lägger till sidnummer i ett PDF-dokument
	err = pdf.AddPageNum()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
