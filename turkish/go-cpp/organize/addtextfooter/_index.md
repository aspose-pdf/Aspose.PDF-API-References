---
title: "AddTextFooter"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesinin altbilgi kısmına metin ekle."
type: docs
url: /tr/go-cpp/organize/addtextfooter/
---

_PDF-dokümanının altbilgi kısmına metin ekle._

```go
func (document *Document) AddTextFooter(footer string) error
```

**Parameters**: 
  * **footer** - pages footer

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
	// AddTextFooter(footer string) PDF belgesinin Altbilgisinde metin ekler
	err = pdf.AddTextFooter("Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_AddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
