---
title: "PageIsBlank"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanındaki sayfanın boş olup olmadığını döndür."
type: docs
url: /tr/go-cpp/core/pageisblank/
---

_PDF-belgesindeki sayfanın boş olduğunu döndür._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// PageIsBlank(num int32) PDF-belgesindeki sayfanın boş olduğunu döndürür.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
