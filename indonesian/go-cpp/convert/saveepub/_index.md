---
title: "SaveEpub"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Epub-document."
type: docs
url: /id/go-cpp/convert/saveepub/
---

_Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Epub-document._

```go
func (document *Document) SaveEpub(filename string) error
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
	// SaveEpub(filename string) menyimpan PDF-document yang sebelumnya dibuka sebagai Epub-document dengan nama file
	err = pdf.SaveEpub("sample.epub")
	if err != nil {
		log.Fatal(err)
	}
}
```
