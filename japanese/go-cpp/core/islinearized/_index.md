---
title: "IsLinearized"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "ドキュメントがリニアライズされているかどうかを示す値を取得します。"
type: docs
url: /ja/go-cpp/core/islinearized/
---

_ドキュメントがリニアライズされているかどうかを示す値を取得します。_

```go
func (document *Document) IsLinearized() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is linearized
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
	// IsLinearized() はドキュメントがリニアライズされているかどうかを示す値を取得します
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
