---
title: "page_layers"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "페이지의 레이어 이름을 가져옵니다."
type: docs
url: /ko/rust-cpp/organize/page_layers/
---

_페이지의 레이어 이름을 가져옵니다._

```rust
pub fn page_layers(&self, num: i32) -> Result<Vec<String>, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(Vec\<String\>)** - the array layers' names
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 파일에서 PDF-document를 엽니다
    let pdf = Document::open("sample_layers.pdf")?;

    // 페이지 1의 레이어 이름을 가져옵니다
    let layers: Vec<String> = pdf.page_layers(1)?;

    println!("Layers on page 1:");
    for name in layers {
        println!("- {}", name);
    }

    Ok(())
}

```