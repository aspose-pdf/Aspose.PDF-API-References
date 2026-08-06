---
title: "clear_meta_info"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "PDF 문서의 모든 메타 정보 값을 삭제합니다."
type: docs
url: /ko/rust-cpp/core/clear_meta_info/
---

_PDF 문서의 모든 메타 정보 값을 삭제합니다._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // PDF 문서의 모든 메타 정보 값을 삭제합니다
    pdf.clear_meta_info()?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```