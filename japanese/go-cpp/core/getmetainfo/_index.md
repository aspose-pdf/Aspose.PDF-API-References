---
title: "GetMetaInfo"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDF ドキュメントのメタ情報の値を取得します。"
type: docs
url: /ja/go-cpp/core/getmetainfo/
---

_PDF ドキュメントのメタ情報の値を取得します。_

```go
func (document *Document) GetMetaInfo(key string) (string, error)
```

**Parameters**: 
  * **key** - key whose value to get

**Return**: 
  * **string** - value associated with the specified key
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf.Close()
	// GetMetaInfo(key string) は PDF ドキュメントのメタ情報の値を取得します
	value, err := pdf.GetMetaInfo("Author")
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Author: ", value)
}
```
