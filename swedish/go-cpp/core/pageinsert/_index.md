---
title: "PageInsert"
second_title: "Aspose.PDF för Go via C++"
description: "Infoga ny sida på den angivna positionen i PDF-dokument."
type: docs
url: /sv/go-cpp/core/pageinsert/
---

_Infoga en ny sida på den angivna positionen i PDF-dokumentet._

```go
func (document *Document) PageInsert(num int32) error
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
	// PageInsert(num int32) infogar en ny sida på den angivna positionen i PDF-dokumentet
	err = pdf.PageInsert(1)
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
