---
title: "PageMergeLayers"
second_title: "Aspose.PDF for Go via C++"
description: "Sayfadaki tüm katmanları, belirtilen yeni katman adıyla tek bir katmanda birleştir."
type: docs
url: /tr/go-cpp/organize/pagemergelayers/
---

_Sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmana birleştir._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

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
	// PageMergeLayers(num int32, newLayerName string) sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmana birleştirir
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
