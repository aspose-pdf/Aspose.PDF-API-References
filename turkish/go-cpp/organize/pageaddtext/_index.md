---
title: "PageAddText"
second_title: "Aspose.PDF for Go via C++"
description: "Sayfaya metin ekle."
type: docs
url: /tr/go-cpp/organize/pageaddtext/
---

_Sayfaya metin ekle._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// PageAddText(num int32, addText string) sayfaya metin ekler
	err = pdf.PageAddText(1, "added text")
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
