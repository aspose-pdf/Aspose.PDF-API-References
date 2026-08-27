---
title: "Bytes"
second_title: "Aspose.PDF for Go via C++"
description: "以字节切片返回 PDF 文档的内容。"
type: docs
url: /zh/go-cpp/core/bytes/
---

_返回 PDF-document 的内容作为字节切片。_

```go
func (document *Document) Bytes() ([]byte, error)
```

**Parameters**: 

**Return**:
  * **\[\]byte** - raw bytes of the PDF-document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
        "github.com/aspose-pdf/aspose-pdf-go-cpp"
        "log"
        "os"
)

func main() {
        // New 创建一个新的 PDF-document
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes 返回 PDF-document 的内容作为字节切片
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // 将字节切片保存到文件。
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
