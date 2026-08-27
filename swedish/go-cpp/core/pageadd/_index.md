---
title: "PageAdd"
second_title: "Aspose.PDF för Go via C++"
description: "Lägg till ny sida i PDF-dokument."
type: docs
url: /sv/go-cpp/core/pageadd/
---

_Lägg till en ny sida i PDF-dokumentet._

```go
func (document *Document) PageAdd() error
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
	// PageAdd() lägger till en ny sida i PDF-dokumentet
	err = pdf.PageAdd()
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
