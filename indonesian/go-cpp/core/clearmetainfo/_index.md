---
title: "ClearMetaInfo"
second_title: "Aspose.PDF untuk Go via C++"
description: "Menghapus semua nilai informasi meta dari PDF-document."
type: docs
url: /id/go-cpp/core/clearmetainfo/
---

_Menghapus semua nilai informasi meta dari PDF-document._

```go
func (document *Document) ClearMetaInfo() error
```

**Parameters**: 

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
	// ClearMetaInfo() menghapus semua nilai informasi meta dari PDF-document
	err = pdf.ClearMetaInfo()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_ClearMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
