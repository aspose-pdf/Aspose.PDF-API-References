---
title: "UnembedFonts"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-document'tan gömülü yazı tiplerini kaldır."
type: docs
url: /tr/go-cpp/organize/unembedfonts/
---

_PDF-dokümanından yazı tiplerini gömülü olmaktan çıkar._

```go
func (document *Document) UnembedFonts() error
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
        // UnembedFonts() PDF-dokümanından yazı tiplerini gömülü olmaktan çıkarır
        err = pdf.UnembedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
        err = pdf.SaveAs("sample_UnembedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
