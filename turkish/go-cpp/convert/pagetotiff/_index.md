---
title: "PageToTiff"
second_title: "Aspose.PDF for Go via C++"
description: "Belirtilen sayfayı Tiff-görüntüsü olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/pagetotiff/
---

_Belirtilen sayfayı Tiff-görüntüsü olarak dönüştür ve kaydet._

```go
func (document *Document) PageToTiff(num int32, resolution_dpi int32, filename string) error
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
	// PageToTiff(num int32, resolution_dpi int32, filename string) belirtilen sayfayı Tiff-görüntüsü dosyası olarak kaydeder
	err = pdf.PageToTiff(1, 100, "sample_page1.tiff")
	if err != nil {
		log.Fatal(err)
	}
}
```
