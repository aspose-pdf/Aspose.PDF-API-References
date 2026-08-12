---
title: "character_count"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanındaki karakter sayısını döndürür."
type: docs
url: /tr/rust-cpp/core/character_count/
---

_PDF-dökümanındaki karakter sayısını döndürür._

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dökümanındaki karakter sayısını döndür
    let count = pdf.character_count()?;

    // Karakter sayısını yazdır
    println!("Character count: {}", count);

    Ok(())
}

```