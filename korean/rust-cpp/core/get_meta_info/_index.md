---
title: "get_meta_info"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document의 메타 정보 값을 가져옵니다."
type: docs
url: /ko/rust-cpp/core/get_meta_info/
---

_PDF-document의 메타 정보 값을 가져옵니다._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF-document의 메타 정보 값을 가져옵니다
    let author = pdf.get_meta_info("Author")?;

    // 결과를 출력합니다
    println!("Author: {}", author);

    Ok(())
}

```