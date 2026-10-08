<h1 align="center">Dondi</h1>
<p align="center">Arif Anıl Dondurmacı · Kurucu &amp; Ürün Mimarı</p>
<p align="center"><strong>AI sistemleri · Runtime mühendisliği · Geliştirici araçları</strong></p>
<p align="center">
  <a href="https://github.com/afimeth/software-interview-portfolio">Mühendislik portföyü</a> ·
  <a href="https://github.com/afimeth/software-interview-portfolio/blob/main/EVALUATION.md">Değerlendirme ve sınırlar</a> ·
  <a href="https://afimeth.github.io/design-engineering-product-lab/">Ürün demosu</a> ·
  <a href="README.md">English</a>
</p>

---

Hata davranışı açık, testleri incelenebilir agent runtime'ları, değerlendirme araçları ve backend iş akışları geliştiriyorum. Odağım; önerilen bir eylem, yürütülen işlem ve sistemin kanıtla destekleyebildiği sonuç arasındaki sınır.

**AI sistemleri, backend/workflow mühendisliği ve geliştirici araçları alanlarında remote çalışmaya açığım.**

## Seçilmiş mühendislik çalışmaları

| Proje | İncelenebilecek mekanizma |
|---|---|
| **[Agent runtime recovery](https://github.com/afimeth/agent-runtime-recovery-lab)** | SQLite üzerinde dispatch durumu, tekrar yürütmenin bastırılması ve belirsiz sonuçların kontrollü ele alınması. |
| **[Retrieval evaluation](https://github.com/afimeth/evidence-rag-eval-lab)** | Lexical retrieval, kaynağa bağlı atıflar, yanıttan kaçınma ve adversarial değerlendirme fixture'ları. |
| **[Scoped tool gateway](https://github.com/afimeth/scoped-tool-gateway-lab)** | Tool kapsamı, süre sonu, atomik kullanım bütçesi ve açık ret/audit davranışı. |
| **[Go workflow runtime](https://github.com/afimeth/workflow-runtime-oss-lab)** | DAG yürütme, sınırlı eşzamanlılık, güvenli retry sözleşmeleri, iptal ve journal recovery. |
| **[Transactional backend](https://github.com/afimeth/durable-backend-systems-lab)** | Payload'a bağlı idempotency, atomik outbox yazımı ve recovery odaklı backend testleri. |

**[Sekiz lab, sabitlenmiş kaynak sürümleri ve CI kayıtları →](https://github.com/afimeth/software-interview-portfolio/blob/main/PORTFOLIO_INDEX.md)**

<details>
<summary><strong>Ürün sistemleri, arayüz tasarımı ve Web3</strong></summary>

**[Realtime product state](https://github.com/afimeth/realtime-product-systems-lab)** — cursor replay, snapshot recovery ve yavaş tüketiciler için sınırlı kuyruklar.

**[Product interface](https://github.com/afimeth/design-engineering-product-lab)** — tarayıcı etkileşim testleri ve otomatik erişilebilirlik kontrolleri bulunan React/TypeScript session journal. [Demoyu aç](https://afimeth.github.io/design-engineering-product-lab/).

**[EVM security mechanisms](https://github.com/afimeth/solidity-multichain-security-lab)** — erişim kontrolü, replay domain, slippage, reentrancy ve conservation invariant'ları için yerel Foundry testleri.

**[Coding-agent evaluation fixture](https://github.com/afimeth/software-interview-portfolio/tree/main/evaluator)** — ortak test suite'i üzerinden değerlendirilen hatalı patch'ler, geçerli bir refactor ve eksik specification vakası.

</details>

## Çalışma yaklaşımım

**Davranışı tanımla → mekanizmayı uygula → hata durumlarını test et → sonucu incele → sınırı belgele.**

Python · Go · TypeScript / React · SQLite · Solidity / Foundry

Public lab'ler sentetik girdilerle geliştirilmiş, AI destekli implementasyonlardır. Her birinde çalıştırma yönergesi ve açık kapsam sınırları bulunur; portföy kaynak sürümlerini ve kayıtlı CI kanıtlarını bağlar. Bunlar somut mühendislik mekanizmalarını gösterir; tek başına production kabulü, bağımsız güvenlik denetimi veya genel benchmark sonucu değildir. [Değerlendirmeyi oku](https://github.com/afimeth/software-interview-portfolio/blob/main/EVALUATION.md).

## New4

**New4U / Orkestral**'ı özel olarak geliştiriyorum: modeller, araçlar ve yürütme yüzeyleri arasında iş sürekliliğini koruyan bir ortam. Public lab'ler, private ürünü veya korpusunu yayımlamadan seçilmiş mühendislik mekanizmalarını görünür kılar. [n4u.tech](https://n4u.tech)

---

**İletişim:** [E-posta](mailto:anildondurmaci2@gmail.com) · [LinkedIn](https://www.linkedin.com/in/arif-anil-dondurmaci-0a8067160/) · [GitHub](https://github.com/afimeth)
