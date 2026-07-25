---
title: "AddTextFooter"
second_title: "Aspose.PDF untuk Go via C++"
description: "Tambahkan teks di Footer PDF-document."
type: docs
url: /id/go-cpp/organize/addtextfooter/
---

_Tambahkan teks di Footer PDF-document._

```go
func (document *Document) AddTextFooter(footer string) error
```

**Parameters**: 
  * **footer** - pages footer

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
	// AddTextFooter(footer string) menambahkan teks di Footer PDF-document
	err = pdf.AddTextFooter("Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
	err = pdf.SaveAs("sample_AddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
