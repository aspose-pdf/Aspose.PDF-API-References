---
title: "Kapat"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dökümanı için ayrılan kaynakları serbest bırak."
type: docs
url: /tr/go-cpp/core/close/
---

_PDF-document için ayrılan kaynakları serbest bırak._

```go
func (document *Document) Close() error
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
	// New yeni bir PDF belgesi oluşturur
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
