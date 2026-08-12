---
title: "PageRemoveImages"
second_title: "Aspose.PDF for Go via C++"
description: "Sayfadaki görüntüleri kaldır."
type: docs
url: /tr/go-cpp/organize/pageremoveimages/
---

_Sayfadaki görselleri kaldır._

```go
func (document *Document) PageRemoveImages(num int32) error
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
	// PageRemoveImages(num int32) sayfadaki görselleri kaldırır
	err = pdf.PageRemoveImages(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_page1_RemoveImages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
