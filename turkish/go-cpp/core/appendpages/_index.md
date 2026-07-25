---
title: "AppendPages"
second_title: "Aspose.PDF for Go via C++"
description: "Başka bir PDF-dökümandan seçilen sayfaları ekle."
type: docs
url: /tr/go-cpp/core/appendpages/
---

_Başka bir PDF-dokümanından seçilen sayfaları ekle._

```go
func (document *Document) AppendPages(anotherdocument *Document, pagerange string) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance
  * **pagerange** - string that specifies which pages to append. Supports individual pages, ranges, and open-ended intervals. For example: "1,3,5", "2-4", "-3", "4-", or "-" for all pages

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// Open(filename string) belirtilen dosya adıyla başka bir PDF belgesini açar
	anotherpdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer anotherpdf.Close()
	// AppendPages(anotherdocument *Document, pagerange string) başka bir PDF-dokümanından belirli sayfaları ekler.
	err = pdf.AppendPages(anotherpdf, "1,3")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_AppendPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
