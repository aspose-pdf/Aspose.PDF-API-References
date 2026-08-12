---
title: "AddTextHeader"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesinin üstbilgi kısmına metin ekle."
type: docs
url: /tr/go-cpp/organize/addtextheader/
---

_PDF belgesinin başlığına metin ekle._

```go
func (document *Document) AddTextHeader(header string) error
```

**Parameters**: 
  * **header** - pages header

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
	// AddTextHeader(header string) PDF belgesinin başlığına metin ekler
	err = pdf.AddTextHeader("Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_AddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
