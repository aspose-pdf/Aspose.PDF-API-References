---
title: "OptimizeFileSize"
second_title: "Aspose.PDF для Go через C++"
description: "Оптимизировать размер PDF-документа с качеством сжатия изображений."
type: docs
url: /ru/go-cpp/organize/optimizefilesize/
---

_Оптимизировать размер PDF-документа с качеством сжатия изображений._

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
        // Open(filename string) открывает PDF-документ с именем файла
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() освобождает выделенные ресурсы для PDF-документа
        defer pdf.Close()
        // OptimizeFileSize(imageQuality int32) оптимизирует размер PDF-документа с качеством сжатия изображений
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
