---
title: "SplitDocument"
second_title: "Aspose.PDF untuk Go via C++"
description: "Buat beberapa dokumen PDF baru dengan mengekstrak halaman dari dokumen PDF sumber."
type: docs
url: /id/go-cpp/core/splitdocument/
---

_Buat beberapa dokumen PDF baru dengan mengekstrak halaman dari dokumen PDF sumber._

```go
func SplitDocument(document *Document, pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **document** - pointer to document
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"log"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
)

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf_split.Close()

	// SplitDocument(document *Document, pagerange string) membuat beberapa dokumen PDF baru
	pdfs, err := asposepdf.SplitDocument(pdf_split, "1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Simpan setiap dokumen PDF yang dipisah sebagai file terpisah
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_SplitDocument_part%d.pdf", i+1)
		// SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
