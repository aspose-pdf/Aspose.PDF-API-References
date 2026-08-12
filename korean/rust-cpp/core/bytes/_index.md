---
title: "바이트"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서의 내용을 바이트 벡터로 반환합니다."
type: docs
url: /ko/rust-cpp/core/bytes/
---

_PDF 문서의 내용을 바이트 벡터로 반환합니다._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 새 PDF 문서를 생성합니다
    let pdf = Document::new()?;

    // PDF 문서의 내용을 바이트 벡터로 반환
    let data = pdf.bytes()?;

    // 바이트 벡터의 길이를 출력
    println!("Length: {}", data.len());

    Ok(())
}

```