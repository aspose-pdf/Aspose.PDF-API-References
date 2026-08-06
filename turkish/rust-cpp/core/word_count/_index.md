---
title: "word_count"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document'teki kelime sayısını döndürür."
type: docs
url: /tr/rust-cpp/core/word_count/
---

_PDF-document'teki kelime sayısını döndürür._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
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

    // PDF-document'teki kelime sayısını döndür
    let count = pdf.word_count()?;

    // Kelime sayısını yazdır
    println!("Word count: {}", count);

    Ok(())
}

```