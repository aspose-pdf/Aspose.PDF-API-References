---
title: "PageInsert"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanında belirtilen konuma yeni sayfa ekle."
type: docs
url: /tr/go-cpp/core/pageinsert/
---

_PDF-belgesinde belirtilen konuma yeni bir sayfa ekle._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// PageInsert(num int32) PDF-belgesinde belirtilen konuma yeni bir sayfa ekler
	err = pdf.PageInsert(1)
	if err != nil {
		log.Fatal(err)
	}
	// Save() daha önce açılmış PDF belgesini kaydeder
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
