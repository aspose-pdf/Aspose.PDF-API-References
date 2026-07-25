---
title: "SaveXps"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Xps-document."
type: docs
url: /id/go-cpp/convert/savexps/
---

_Konversi dan simpan PDF-dokumen yang sebelumnya dibuka sebagai Xps-document._

```go
func (document *Document) SaveXps(filename string) error
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
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// SaveXps(filename string) menyimpan PDF-dokumen yang sebelumnya dibuka sebagai Xps-document dengan nama file
	err = pdf.SaveXps("sample.xps")
	if err != nil {
		log.Fatal(err)
	}
}
```
