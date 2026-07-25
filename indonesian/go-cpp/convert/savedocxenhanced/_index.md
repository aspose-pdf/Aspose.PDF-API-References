---
title: "SaveDocXEnhanced"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai DocX-document dengan Mode Pengakuan Ditingkatkan (tabel dan paragraf yang dapat diedit sepenuhnya)."
type: docs
url: /id/go-cpp/convert/savedocxenhanced/
---

_Konversi dan simpan PDF-dokumen yang sebelumnya dibuka sebagai DocX-document dengan Enhanced Recognition Mode (tabel dan paragraf yang dapat diedit sepenuhnya)._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
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
	// SaveDocX(filename string) menyimpan PDF-dokumen yang sebelumnya dibuka sebagai DocX-document dengan Mode Pengenalan Tingkat Lanjut dengan nama file
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
