---
title: "optimize_file_size"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "이미지 압축 품질을 사용하여 PDF 문서의 크기를 최적화합니다."
type: docs
url: /ko/rust-cpp/organize/optimize_file_size/
---

_이미지 압축 품질을 사용하여 PDF 문서의 크기를 최적화합니다._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // 이미지 압축 품질을 사용하여 PDF 문서의 크기를 최적화
    pdf.optimize_file_size(50)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```