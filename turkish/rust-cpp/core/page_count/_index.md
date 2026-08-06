---
title: "page_count"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF belgesindeki sayfa sayısını döndürür."
type: docs
url: /tr/rust-cpp/core/page_count/
---

_PDF belgesindeki sayfa sayısını döndürür._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
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

    // PDF belgesindeki sayfa sayısını döndür
    let count = pdf.page_count()?;

    // Sayfa sayısını yazdır
    println!("Count: {}", count);

    Ok(())
}

```