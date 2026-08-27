---
title: "PageCharacterCount"
second_title: "Aspose.PDF untuk Go via C++"
description: "Kembalikan jumlah karakter pada halaman yang ditentukan dalam PDF-dokumen."
type: docs
url: /id/go-cpp/core/pagecharactercount/
---

_Mengembalikan jumlah karakter pada halaman tertentu dalam PDF-document._

```go
func (document *Document) PageCharacterCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - character count on the page
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// PageCharacterCount(num int32) mengembalikan jumlah karakter pada halaman tertentu dalam PDF-document.
	page_character_count, err := pdf.PageCharacterCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count on the first page:", page_character_count)
}
```
