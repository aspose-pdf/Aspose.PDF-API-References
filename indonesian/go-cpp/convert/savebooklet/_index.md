---
title: "SaveBooklet"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai PDF-document booklet."
type: docs
url: /id/go-cpp/convert/savebooklet/
---

_Konversi dan simpan PDF-dokumen yang sebelumnya dibuka sebagai PDF-dokumen booklet._

```go
func (document *Document) SaveBooklet(filename string) error
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
	// SaveBooklet(filename string) menyimpan PDF-dokumen yang sebelumnya dibuka sebagai PDF-dokumen booklet dengan nama file
	err = pdf.SaveBooklet("sample_Booklet.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
