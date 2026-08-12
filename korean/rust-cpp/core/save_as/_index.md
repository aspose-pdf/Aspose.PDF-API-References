---
title: "save_as"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "이전에 열었던 PDF 문서를 새 파일 이름으로 저장합니다."
type: docs
url: /ko/rust-cpp/core/save_as/
---

_이전에 열었던 PDF 문서를 새 파일 이름으로 저장합니다._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 새 PDF 문서를 생성합니다
    let pdf = Document::new()?;

    // PDF 문서를 새 파일 이름으로 저장합니다
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```