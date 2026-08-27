---
title: "PageAddText"
second_title: "Aspose.PDF för Go via C++"
description: "Lägg till text på sidan."
type: docs
url: /sv/go-cpp/organize/pageaddtext/
---

_Lägg till text på sidan._

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string) lägger till text på sidan
	err = pdf.PageAddText(1, "added text")
	if err != nil {
		log.Fatal(err)
	}
	// Save() sparar tidigare öppnat PDF-dokument
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
