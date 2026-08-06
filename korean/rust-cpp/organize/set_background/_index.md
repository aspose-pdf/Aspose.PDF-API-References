---
title: "set_background"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "RGB 값을 사용하여 PDF 문서 배경 색상을 설정합니다."
type: docs
url: /ko/rust-cpp/organize/set_background/
---

_RGB 값을 사용하여 PDF 문서 배경 색상을 설정합니다._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일 이름으로 PDF 문서를 엽니다
    let pdf = Document::open("sample.pdf")?;

    // RGB 값을 사용하여 PDF 문서 배경 색상을 설정
    pdf.set_background(200, 100, 101)?;

    // 이전에 열었던 PDF-document을 새 파일 이름으로 저장합니다
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```