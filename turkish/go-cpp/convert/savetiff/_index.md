---
title: "SaveTiff"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını Tiff-dokümanı olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/savetiff/
---

_Daha önce açılmış PDF-dokümanı Tiff-dokümanı olarak dönüştür ve kaydet._

```go
func (document *Document) SaveTiff(filename string, resolution_dpi ...int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **resolution_dpi (optional)** - resolution in DPI of the resulting file, defaults to 100 DPI

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
        // SaveTiff(filename string) daha önce açılmış PDF-dokümanı Tiff-dokümanı olarak dosya adıyla kaydeder
        err = pdf.SaveTiff("sample.tiff")
        if err != nil {
                log.Fatal(err)
        }
}
```
