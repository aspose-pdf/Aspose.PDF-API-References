---
title: "PageToPdf"
second_title: "Aspose.PDF for Go via C++"
description: "Belirtilen sayfayı Pdf olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/pagetopdf/
---

_Belirtilen sayfayı Pdf olarak dönüştür ve kaydet._

```go
func (document *Document) PageToPdf(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **filename** - new filename

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
	// PageToPdf(num int32, filename string) belirtilen sayfayı Pdf dosyası olarak kaydeder
	err = pdf.PageToPdf(1, "sample_page1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
