---
title: "PageAdd"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanına yeni sayfa ekle."
type: docs
url: /tr/go-cpp/core/pageadd/
---

_PDF-document'e yeni sayfa ekle._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// PageAdd() PDF-document'e yeni sayfa ekler
	err = pdf.PageAdd()
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
