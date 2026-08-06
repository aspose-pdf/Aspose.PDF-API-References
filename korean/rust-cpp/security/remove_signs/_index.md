---
title: "remove_signs"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF-document에서 서명을 제거합니다."
type: docs
url: /ko/rust-cpp/security/remove_signs/
---

_PDF 문서에서 서명을 제거합니다._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample_with_sign.pdf"라는 PDF 문서를 엽니다
    let pdf = Document::open("sample_with_sign.pdf")?;

    // PDF 문서에서 서명 제거
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```