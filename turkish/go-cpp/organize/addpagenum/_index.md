---
title: "AddPageNum"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesine sayfa numarası ekle."
type: docs
url: /tr/go-cpp/organize/addpagenum/
---

_Bir PDF belgesine sayfa numarası ekle._

```go
func (document *Document) AddPageNum() error
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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// AddPageNum() bir PDF belgesine sayfa numarası ekler
	err = pdf.AddPageNum()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
