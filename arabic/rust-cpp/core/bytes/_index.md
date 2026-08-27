---
title: "بايت"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يعيد محتويات PDF-document كمتجه بايت."
type: docs
url: /ar/rust-cpp/core/bytes/
---

_يعيد محتويات PDF-document كمتجه بايت._

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
    // إنشاء مستند PDF-document جديد
    let pdf = Document::new()?;

    // إرجاع محتويات PDF-document كمتجه بايت
    let data = pdf.bytes()?;

    // اطبع طول متجه البايت
    println!("Length: {}", data.len());

    Ok(())
}

```