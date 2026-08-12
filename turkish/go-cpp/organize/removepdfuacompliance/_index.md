---
title: "RemovePdfUaCompliance"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-document'tan PDF/UA uyumluluğunu kaldır."
type: docs
url: /tr/go-cpp/organize/removepdfuacompliance/
---

_Bir PDF belgesinden PDF/UA uyumluluğunu kaldır._

```go
func (document *Document) RemovePdfUaCompliance() error
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
	// RemovePdfUaCompliance() PDF belgesinden PDF/UA uyumluluğunu kaldırır
	err = pdf.RemovePdfUaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_RemovePdfUaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
