---
title: "SetMetaInfo"
second_title: "Aspose.PDF untuk Go via C++"
description: "Menetapkan nilai informasi meta pada PDF-document."
type: docs
url: /id/go-cpp/core/setmetainfo/
---

_Menetapkan nilai informasi meta pada PDF-document._

```go
func (document *Document) SetMetaInfo(key, value string) error
```

**Parameters**: 
  * **key** - key whose value to set
  * **value** - value to be set

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
	// SetMetaInfo(key, value string) menetapkan nilai informasi meta pada PDF-document
	err = pdf.SetMetaInfo("Author", "Aspose")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_SetMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
