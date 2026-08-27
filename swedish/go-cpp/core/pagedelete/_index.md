---
title: "PageDelete"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort angiven sida i PDF-dokument."
type: docs
url: /sv/go-cpp/core/pagedelete/
---

_Raderar angiven sida i PDF-dokumentet._

```go
func (document *Document) PageDelete(num int32) error
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
	// PageDelete(num int32) raderar angiven sida i PDF-dokumentet
	err = pdf.PageDelete(1)
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
