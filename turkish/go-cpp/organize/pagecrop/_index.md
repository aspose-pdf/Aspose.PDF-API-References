---
title: "PageCrop"
second_title: "Aspose.PDF for Go via C++"
description: "Sayfayı kırp."
type: docs
url: /tr/go-cpp/organize/pagecrop/
---

_Sayfayı kırp._

```go
func (document *Document) PageCrop(num int32, margin float64) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **margin** - page margin

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
        // PageCrop(num int32, margin float64) sayfayı kırpar
        err = pdf.PageCrop(1, 11.3)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
        err = pdf.SaveAs("sample_page1_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
