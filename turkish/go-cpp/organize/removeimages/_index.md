---
title: "RemoveImages"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesinden görüntüleri kaldır."
type: docs
url: /tr/go-cpp/organize/removeimages/
---

_PDF-dokümanından görüntüleri kaldır._

```go
func (document *Document) RemoveImages() error
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
	// RemoveImages() PDF-dokümanından görüntüleri kaldırır
	err = pdf.RemoveImages()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_RemoveImages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
