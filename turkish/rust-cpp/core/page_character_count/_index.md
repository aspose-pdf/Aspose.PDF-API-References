---
title: "page_character_count"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanındaki belirtilen sayfadaki karakter sayısını döndürür."
type: docs
url: /tr/rust-cpp/core/page_character_count/
---

_PDF-dökümanındaki belirtilen sayfadaki karakter sayısını döndürür._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfa numarasını belirtin (1 tabanlı indeks)
    let page_number = 1;

    // Belirtilen sayfadaki karakter sayısını döndür
    let count = pdf.page_character_count(page_number)?;

    // Karakter sayısını yazdır
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```