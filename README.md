# YOSHIKI MATSUNAGA — NEXSPACE

**Indie AI developer & surveyor apprentice in Kagoshima, Japan.**
I design systems and direct AI models to build them — requirements, architecture, verification and audit are my job; the code is written by AI under that control.

- 🏢 Founder and sole developer of [NEXSPACE](https://www.nexspace.jp)
- 📐 Surveyor apprentice since September 2026 (field work on remote islands) — my field experience feeds directly into the tools I build
- 📄 2 papers on Zenodo ([18922676](https://zenodo.org/records/18922676), [18815443](https://zenodo.org/records/18815443))
- 🛠️ Rust · Tauri · TypeScript · Python · Swift · Flutter · C++
- 📫 contact@nexspace.jp · X [@NEXSPACE_CICAS](https://x.com/NEXSPACE_CICAS)

---

## How I work

I can't write code by hand, and I don't pretend to. What I do instead:

1. **Write the requirements** — including what the system must *refuse* to do (no guessing business rules, no reporting unverified results as done).
2. **Split roles across AI models** — Claude for design, judgment and audit; GPT for counter-checking; Gemini for divergent ideas.
3. **Verify everything** — every project ships a validation record that lists what was tested *and what was not*.

## Products

| Product | What it is | Status |
|---|---|---|
| **JibunSite** | Desktop website builder (Tauri + Rust). AI assembles validated JSON blocks, not raw HTML | Microsoft Store · featured on 窓の杜 |
| **DenkiScope** | Windows power-monitoring tool | Microsoft Store |
| **CRM Task Checker** | iOS app for freelancers: every open case must always hold exactly one "next action" | App Store |
| **CareLingual** | On-premises care-facility support app. LAN-only sync, AES-256-GCM per-device keys, SQLCipher | In development |
| **NGND** | Local server monitoring & defense: quarantine-first ingress control, ClamAV/YARA signature layer | In development |

Source code for commercial products is kept private.

## Research

- **NeutronGate** — a fully local Japanese AI written in Rust, running on CPU only. Core: *360-DQHM*, a holographic associative memory (Vector Symbolic Architecture) in a 360-dimensional complex vector space with phase-resonance similarity. → [overview](https://github.com/NEXSPACE-y/NeutronGate_Auditor)
- **ALSR PoC** — measures how far model inference can go beyond VRAM capacity by streaming weight chunks from RAM. Built to *find where it fails*, not to show off.

## Field tools (surveying)

- **PointCloud Jev** — Windows app for drone photogrammetry point clouds (LAS/LAZ): noise-candidate analysis, GCP-based calibration, SfM re-computation from source photos, JGD2011/JGD2024 CRS output.
- **Total station training simulator** — practice instrument setup without going on site (in progress).

---

<details>
<summary>🇯🇵 日本語</summary>

## 松永 義樹 — NEXSPACE

**鹿児島の個人AI開発者・測量士見習い。**
要件定義・設計・検証・監査は自分で行い、コードはAIに書かせる開発スタイルです。

- [NEXSPACE](https://www.nexspace.jp) 創業者・唯一の開発者
- 2026年9月から測量見習い（離島の現場）。現場で見た課題をそのまま道具にしています
- Zenodoに論文2本
- 連絡先：contact@nexspace.jp

### 作り方

コードは手で書けませんし、書けるふりもしません。その代わりに次のことをしています。

1. **要件を書く**：やってはいけないこと（業務ルールを推測で埋めない、未検証のものを完了扱いしない）まで含めて書く
2. **AIの役割を分ける**：設計・判断・監査はClaude、反証はGPT、発散的な発想はGemini
3. **すべてを検証する**：どのプロジェクトにも「何を検証し、何を検証していないか」を書いた検証記録を付ける

### 製品

- **じぶんサイト**：デスクトップのサイト制作ツール（Microsoft Store、窓の杜掲載）
- **DenkiScope**：Windowsの電力監視ツール（Microsoft Store）
- **CRMタスクチェッカー**：進行中の案件に必ず「次回対応」を1つ持たせるiOSアプリ（App Store）
- **CareLingual**：施設内LANで完結する介護・看護現場支援アプリ（開発中）
- **NGND**：隔離優先のサーバー監視・防御システム（開発中）

販売中・販売予定の製品のソースコードは非公開です。

### 研究

- **NeutronGate**：Rust製・CPUのみで動く完全ローカル日本語AI。中核は360次元複素ベクトル空間のホログラフィック連想記憶「360-DQHM」
- **ALSR PoC**：VRAM容量を超えるモデル推論がどこまで成立するかを測る研究用PoC

### 測量の道具

- **PointCloud Jev**：ドローン写真測量の点群（LAS/LAZ）解析・GCP校正・SfM再計算
- **トータルステーション実習シミュレーター**（開発中）

</details>
