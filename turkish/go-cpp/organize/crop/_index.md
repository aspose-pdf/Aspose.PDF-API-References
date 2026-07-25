---
title: "Crop"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-document sayfalarını kırp."
type: docs
url: /tr/go-cpp/organize/crop/
---

_PDF-belgenin sayfalarını kırp._

```go
func (document *Document) Crop(margin float64) error
```

**Parameters**: 
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
        // Crop(margin float64) PDF-belgenin sayfalarını kırpar
        err = pdf.Crop(0)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
        err = pdf.SaveAs("sample_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
