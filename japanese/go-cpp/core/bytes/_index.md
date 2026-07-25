---
title: "Bytes"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDF ドキュメントの内容をバイトスライスとして返します。"
type: docs
url: /ja/go-cpp/core/bytes/
---

_PDF ドキュメントの内容をバイトスライスとして返します。_

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
        // New は新しい PDFドキュメントを作成します。
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes は PDF ドキュメントの内容をバイトスライスとして返します
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // バイトスライスをファイルに保存します。
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
