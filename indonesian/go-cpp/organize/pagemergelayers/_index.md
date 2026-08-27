---
title: "PageMergeLayers"
second_title: "Aspose.PDF untuk Go via C++"
description: "Gabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan."
type: docs
url: /id/go-cpp/organize/pagemergelayers/
---

_Gabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan._

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
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// PageMergeLayers(num int32, newLayerName string) menggabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
