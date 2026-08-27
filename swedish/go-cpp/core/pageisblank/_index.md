---
title: "PageIsBlank"
second_title: "Aspose.PDF för Go via C++"
description: "Returnera om sidan är tom i PDF-dokument."
type: docs
url: /sv/go-cpp/core/pageisblank/
---

_Returnerar att sidan är tom i PDF-dokumentet._

```go
func (document *Document) PageIsBlank(num int32) (bool, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **bool** - the page is blank
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// PageIsBlank(num int32) returnerar att sidan är tom i PDF-dokumentet.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Skriv ut
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
