---
title: "OptimizeFileSize"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-document boyutunu görüntü sıkıştırma kalitesiyle optimize et."
type: docs
url: /tr/go-cpp/organize/optimizefilesize/
---

_PDF-belgenin boyutunu görüntü sıkıştırma kalitesiyle optimize et._

```go
func (document *Document) OptimizeFileSize(imageQuality int32) error
```

**Parameters**: 
  * **imageQuality** - image compression quality 

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
        // OptimizeFileSize(imageQuality int32) PDF-belgenin boyutunu görüntü sıkıştırma kalitesiyle optimize eder
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
