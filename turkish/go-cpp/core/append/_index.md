---
title: "Append"
second_title: "Aspose.PDF for Go via C++"
description: "Başka bir PDF-dökümandan sayfaları ekle."
type: docs
url: /tr/go-cpp/core/append/
---

_Başka bir PDF belgesinden sayfaları ekle._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {

	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()

	// Open(filename string) belirtilen dosya adıyla başka bir PDF belgesini açar
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) başka bir PDF belgesinden sayfaları ekler.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
