---
title: "SaveSvgZip"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını SVG arşivi olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/savesvgzip/
---

_Dönüştür ve daha önce açılmış PDF-belgesini SVG-arşivi olarak kaydet._

```go
func (document *Document) SaveSvgZip(filename string) error
```

**Parameters**: 
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
	// SaveSvgZip(filename string) daha önce açılmış PDF-belgesini SVG-arşivi olarak dosya adıyla kaydeder
	err = pdf.SaveSvgZip("sample_svg.zip")
	if err != nil {
		log.Fatal(err)
	}
}
```
