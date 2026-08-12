---
title: "RemoveAnnotations"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesinden ek açıklamaları kaldır."
type: docs
url: /tr/go-cpp/organize/removeannotations/
---

_PDF belgesinden ek açıklamaları kaldır._

```go
func (document *Document) RemoveAnnotations() error
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
	// RemoveAnnotations() PDF belgesinden ek açıklamaları kaldırır
	err = pdf.RemoveAnnotations()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_RemoveAnnotations.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
