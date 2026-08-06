---
title: "get_meta_info"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF belgesinin meta bilgi değerini alır."
type: docs
url: /tr/rust-cpp/core/get_meta_info/
---

_PDF belgesinin meta bilgi değerini alır._

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
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF belgesinin meta bilgi değerini al
    let author = pdf.get_meta_info("Author")?;

    // Sonucu yazdır
    println!("Author: {}", author);

    Ok(())
}

```