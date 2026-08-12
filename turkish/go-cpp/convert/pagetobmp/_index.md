---
title: "PageToBmp"
second_title: "Aspose.PDF for Go via C++"
description: "Belirtilen sayfayı Bmp-görüntüsü olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/pagetobmp/
---

_Belirtilen sayfayı Bmp-görüntüsü olarak dönüştür ve kaydet._

```go
func (document *Document) PageToBmp(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
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
	// PageToBmp(num int32, resolution_dpi int32, filename string) belirtilen sayfayı Bmp-görüntü dosyası olarak kaydeder
	err = pdf.PageToBmp(1, 100, "sample_page1.bmp")
	if err != nil {
		log.Fatal(err)
	}
}
```
