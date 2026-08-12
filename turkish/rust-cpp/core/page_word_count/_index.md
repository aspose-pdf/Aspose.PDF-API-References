---
title: "page_word_count"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document'teki belirtilen sayfadaki kelime sayısını döndürür."
type: docs
url: /tr/rust-cpp/core/page_word_count/
---

_PDF-document'teki belirtilen sayfadaki kelime sayısını döndürür._

```rust
pub fn page_word_count(&self) -> Result<i32, PdfError>
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

    // Belirtilen sayfadaki kelime sayısını döndür
    let count = pdf.page_word_count(page_number)?;

    // Kelime sayısını yazdır
    println!("Word count on page {}: {}", page_number, count);

    Ok(())
}

```