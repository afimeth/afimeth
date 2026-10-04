<p align="center">
  <img src="./assets/profile-evidence-iceberg.svg" alt="Arif Anıl Dondurmacı — AI / Agentic Systems mühendislik kanıt yüzeyi" width="100%" />
</p>

# Arif Anıl Dondurmacı

**Founder & Product Architect — AI / Agentic Systems**

AI sistemlerinde demo bittikten sonra önemli hale gelen katmanlarla ilgileniyorum: dayanıklı state, failure recovery, evals, scoped tools, provenance, routing ve kanıta bağlı execution.

**New4U / Orkestral**'ı özel olarak geliştiriyorum — [n4u.tech](https://n4u.tech).  
Buradaki public repolar **ürünün kopyası değil**. Bilerek daha küçük ve incelenebilir tutuluyorlar: çalışan mekanizmalar, sentetik fixture'lar, testler, receipt'ler, referanslar ve açık limitation'lar.

> **Mekanizmayı aç. Mitolojiyi değil.**

[English](README.md) · Türkçe

## Public evidence

- **[agent-runtime-recovery-lab](https://github.com/afimeth/agent-runtime-recovery-lab)** — durable dispatch marker'ları, konservatif crash recovery ve replay suppression.
- **[evidence-rag-eval-lab](https://github.com/afimeth/evidence-rag-eval-lab)** — deterministic retrieval eval, citation binding, abstention ve adversarial fixture'lar.
- **[scoped-tool-gateway-lab](https://github.com/afimeth/scoped-tool-gateway-lab)** — scoped capability gate'leri, expiry, budget, denial audit ve replay testleri.
- **[workflow-runtime-oss-lab](https://github.com/afimeth/workflow-runtime-oss-lab)** — Go DAG runtime, bounded concurrency, explicit retry semantiği ve journal recovery.
- **[durable-backend-systems-lab](https://github.com/afimeth/durable-backend-systems-lab)** — transactional idempotency, atomic outbox ve crash-safe backend fixture'ları.
- **[realtime-product-systems-lab](https://github.com/afimeth/realtime-product-systems-lab)** — async product-state ve realtime davranış.
- **[solidity-multichain-security-lab](https://github.com/afimeth/solidity-multichain-security-lab)** — Solidity / multichain security fixture'ları ve invariant odaklı testler.
- **[design-engineering-product-lab](https://github.com/afimeth/design-engineering-product-lab)** — product-facing implementation örneği.
- **[software-interview-portfolio](https://github.com/afimeth/software-interview-portfolio)** — public lab'ler için engineering evidence index.

## Bu repolar nasıl okunmalı

```text
claim
  -> implementation
  -> fixture / input
  -> test / eval
  -> observed output / receipt
  -> limitation
```

README yalnızca iceberg'in üst kısmı. İsteyen engineer fixture'lara, failure case'lere, receipt'lere, provenance'a, chronology'ye ve architecture'a kadar iner.

Bir runtime'ın incelenebilir olması için hazır UI şart değil:

```text
input -> headless runtime -> output -> receipt
```

CLI, IDE, web, desktop veya automation yüzeyi aynı runtime contract'ın farklı projection'ları olabilir.

## Çalışma prensipleri

```text
evidence > claims
runtime > UI
meaning > implementation
receipts > screenshots
explicit limits > polished certainty
```

Human input compressed, çok dilli veya informal olabilir. Source meaning korunur; sonra current consumer için en uygun representation'a projection yapılır: English, structured JSON/YAML, Go-like syntax, graph/AST, compact relay language veya model-specific encoding.

**One semantic object, many valid encodings.**

## Kullandığım araçlar

Python · Go · TypeScript / React · Kotlin / Jetpack Compose · Flutter / Dart · SQLite / PostgreSQL · Docker · local ve cloud model runtime'ları

## İletişim

[n4u.tech](https://n4u.tech) · [GitHub](https://github.com/afimeth) · [LinkedIn](https://www.linkedin.com/in/arif-anil-dondurmaci-0a8067160/) · [Email](mailto:anildondurmaci2@gmail.com)
