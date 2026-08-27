---
title: "PageAddPageNum"
second_title: "Aspose.PDF för Go via C++"
description: "Lägg till sidnummer på sidan."
type: docs
url: /sv/go-cpp/organize/pageaddpagenum/
---

_Lägg till sidnummer på sidan._

```go
func (document *Document) PageAddPageNum(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageAddPageNum(num int32) lägger till sidnummer på sidan
	err = pdf.PageAddPageNum(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_page1_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
