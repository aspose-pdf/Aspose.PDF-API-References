---
title: "Flatten"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesini düzleştir."
type: docs
url: /tr/go-cpp/organize/flatten/
---

_PDF-dokümanını düzleştir._

```go
func (document *Document) Flatten() error
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
	// Flatten() PDF-dokümanını düzleştirir
	err = pdf.Flatten()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_Flatten.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
