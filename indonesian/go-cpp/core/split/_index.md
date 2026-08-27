---
title: "Split"
second_title: "Aspose.PDF untuk Go via C++"
description: "Buat beberapa dokumen PDF baru dengan mengekstrak halaman dari dokumen PDF saat ini."
type: docs
url: /id/go-cpp/core/split/
---

_Buat beberapa dokumen PDF baru dengan mengekstrak halaman dari dokumen PDF saat ini._

```go
func (document *Document) Split(pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf_split.Close()

	// Split(pagerange string) membuat beberapa dokumen PDF baru dengan mengekstrak halaman dari dokumen PDF saat ini
	pdfs, err := pdf_split.Split("1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Simpan setiap dokumen PDF yang dipisah sebagai file terpisah
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_Split_part%d.pdf", i+1)
		// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
