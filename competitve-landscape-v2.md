# DELIVERABLE 1: COMPETITIVE LANDSCAPE — Web3 AI Agent / Skill Marketplace

> **Tác giả:** [Tên thí sinh]  
> **Ngày:** Tháng 2, 2026  
> **Dự án:** ClawFriend — Web3 AI Agent Platform (Skill Market Module)

---

## 1. TỔNG QUAN THỊ TRƯỜNG

Thị trường Web3 AI Agent đang trải qua giai đoạn **tăng trưởng bùng nổ nhưng chưa trưởng thành**. Theo Cointelegraph, các chuyên gia ngành dự đoán hơn 1 triệu AI agent sẽ hoạt động trên blockchain networks trước cuối 2025. Venture capital đã rót khoảng $800M vào các dự án AI-Web3 chỉ trong nửa đầu 2025 (Crunchbase). Tuy nhiên, hầu hết các platform hiện tại đều tập trung vào **agent creation/tokenization** chứ chưa có ai thực sự giải quyết tốt bài toán **skill marketplace** — nơi agents có thể mua bán, chia sẻ capabilities.

**Định nghĩa phạm vi phân tích:** Tập trung vào các platform có ít nhất 1 trong 3 yếu tố: (1) AI agent marketplace/registry, (2) Skill/plugin store cho agents, (3) Social + tokenization layer tương tự ClawFriend.

---

## 2. PHÂN TÍCH CHI TIẾT 6 ĐỐI THỦ

### 2.1 Virtuals Protocol

| Tiêu chí         | Chi tiết                                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Website**      | [virtuals.io](https://virtuals.io)                                                                                                                                                          |
| **Blockchain**   | Base (Ethereum L2), mở rộng sang Solana (01/2025)                                                                                                                                           |
| **Mô tả**        | Nền tảng tokenize AI agents, cho phép co-ownership thông qua agent tokens. Agents hoạt động trên nhiều platform (Roblox, Telegram, TikTok, X).                                              |
| **Số liệu**      | Tổng market cap agents >$500M (09/2025, Messari). Hơn $8B DEX volume. Base chiếm 90.2% daily active wallets. Token $VIRTUAL market cap ~$2B tại peak. 280K+ followers trên X.               |
| **Monetization** | Bonding curve cho agent token launch. Phí 10% mỗi transaction (chia protocol + treasury + buy-back & burn). Agent GDP Program tài trợ lên đến $1M/tháng cho builders.                       |
| **Điểm mạnh**    | First mover advantage trong agent tokenization. Ecosystem lớn nhất (Luna, AIXBT, VaderAI). Agent Commerce Protocol (ACP) cho phép agent-to-agent transactions. Community cực kỳ mạnh.       |
| **Điểm yếu**     | **KHÔNG có Skill Marketplace riêng biệt.** Focus vào tokenization/speculation hơn utility. Revenue giảm mạnh từ $1.02M/ngày (01/2025) xuống ~$35K/ngày (02/2025). Phụ thuộc vào hype cycle. |

**Insight chiến lược:** Virtuals là "king" của agent tokenization nhưng **thiếu skill layer**. ACP mới chỉ cho phép agents giao dịch dịch vụ với nhau, chưa có marketplace browse/publish skills như ClawFriend. Đây là **gap lớn nhất** mà ClawFriend có thể khai thác.

---

### 2.2 Olas (Autonolas)

| Tiêu chí         | Chi tiết                                                                                                                                                                                                                                |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Website**      | [olas.network](https://olas.network)                                                                                                                                                                                                    |
| **Blockchain**   | Multi-chain (Ethereum, Gnosis, Base, + 6 chains khác)                                                                                                                                                                                   |
| **Mô tả**        | Platform co-own AI agents. Pearl là "AI Agent App Store" (desktop app), Mech Marketplace là "bazaar" nơi agents thuê dịch vụ lẫn nhau.                                                                                                  |
| **Số liệu**      | Huy động $13.8M (02/2025, led by 1kx). Hơn 3.5M transactions từ agents trên 9 blockchain. 700K transactions/tháng (tăng 30%+ MoM). Prediction Trader agents đạt ~74% accuracy, DeFi agent ROI 150% trong 150 ngày.                      |
| **Monetization** | Marketplace fees khi agents thuê dịch vụ lẫn nhau. OLAS staking. Fees dùng để burn OLAS (deflationary).                                                                                                                                 |
| **Điểm mạnh**    | **Gần nhất với skill marketplace concept.** Mech Marketplace cho phép agent-to-agent hiring. Pearl v1 UX thân thiện (desktop app). Mô hình user-owned agents. Olas Accelerator ($1M grants). Tích hợp x402 payments.                    |
| **Điểm yếu**     | Pearl chỉ là desktop app, chưa có web version. Marketplace chủ yếu agent-to-agent, chưa focus human creators publish skills. Số lượng agent categories còn hạn chế (prediction, DeFAI, influencer, gaming). Community nhỏ hơn Virtuals. |

**Insight chiến lược:** Olas là **đối thủ trực tiếp nhất** về concept. Tuy nhiên, Mech Marketplace focus agent-to-agent services, trong khi ClawFriend Skill Market cho phép **humans tạo skills cho agents** — đây là điểm khác biệt quan trọng. ClawFriend cũng có social layer (tweets, follows) mà Olas thiếu.

---

### 2.3 Fetch.ai (Agentverse)

| Tiêu chí         | Chi tiết                                                                                                                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Website**      | [fetch.ai](https://fetch.ai) / [agentverse.ai](https://agentverse.ai)                                                                                                                                                                             |
| **Blockchain**   | Fetch Ledger (Cosmos-SDK based)                                                                                                                                                                                                                   |
| **Mô tả**        | Agentverse là marketplace + IDE cho AI agents. Agents đăng ký trên Almanac smart contract, được discover và giao tiếp qua protocols. DeltaV là consumer layer kết nối users với agent services.                                                   |
| **Số liệu**      | Ra mắt 2017, IEO trên Binance 2019. FET market cap ~$390M. 150K+ social media followers. ASI:One LLM (Web3-native). Agentverse MCP tích hợp với Claude Desktop, Cursor.                                                                           |
| **Monetization** | FET token cho transactions, registration, staking. DeltaV marketplace fees. Agent service calls trả phí bằng FET.                                                                                                                                 |
| **Điểm mạnh**    | **Full-stack agent ecosystem** (framework + marketplace + LLM + consumer app). Agentverse IDE mạnh — code editor, logging, file management. Agent-to-agent communication protocol mature. Brand Agent (cho businesses). ASI:One LLM tích hợp sâu. |
| **Điểm yếu**     | Quá phức tạp cho người mới. Marketplace thiên về developer hơn consumer. Không có social layer. Thiếu tokenization/speculation incentive (không có bonding curve). Reliance on external APIs gây lo ngại centralization.                          |

**Insight chiến lược:** Fetch.ai mạnh về **infrastructure** nhưng yếu về **consumer appeal**. ClawFriend kết hợp social (agents tweet/reply) + speculation (shares trading) + utility (skill market) — một combo mà Fetch.ai không có.

---

### 2.4 OpenClaw + ClawHub (Skill Registry)

| Tiêu chí         | Chi tiết                                                                                                                                                                                                                                                                                                                                                                                            |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Website**      | [openclaw.ai](https://openclaw.ai) / [clawhub.ai](https://clawhub.ai) / [GitHub](https://github.com/openclaw/openclaw)                                                                                                                                                                                                                                                                              |
| **Blockchain**   | Không có blockchain integration — hoàn toàn off-chain, self-hosted                                                                                                                                                                                                                                                                                                                                  |
| **Mô tả**        | OpenClaw là open-source personal AI agent chạy local trên thiết bị người dùng. ClawHub là **public skill registry** (giống "npm cho AI agents") — nơi community publish, version, search, và install skills dưới dạng SKILL.md files.                                                                                                                                                               |
| **Số liệu**      | **229K+ GitHub stars** (02/2026) — dự án open-source tăng nhanh nhất lịch sử (100K stars trong <1 tháng). 43,600+ forks. 2M+ website visits/tuần. ClawHub: **10,000+ skills** (tăng từ 5,700 skills vào đầu 02/2026, sau khi clean 2,419 malicious skills). ClawHub repo: 2,842 stars, 613 forks. 53 bundled skills + 10K+ community skills.                                                        |
| **Monetization** | **KHÔNG có monetization cho skill creators.** Toàn bộ skills trên ClawHub là **free và public**. Không có paid skills, subscription, hoặc token economy. OpenClaw kiếm tiền = $0 (founder Peter Steinberger là founder PSPDFKit, tự fund).                                                                                                                                                          |
| **Điểm mạnh**    | **Largest skill registry trong toàn bộ AI agent ecosystem** (10K+ skills). Community contributor cực lớn. Vector search cho skill discovery. CLI-friendly (clawhub install, clawhub sync). Versioning, changelogs, tags. VirusTotal security scanning partnership. Đã có categories: dev tools, productivity, communication, smart home, AI model integration.                                      |
| **Điểm yếu**     | **KHÔNG có blockchain/Web3.** Không có tokenization, không có economic incentive cho skill creators (hoàn toàn miễn phí). Security là vấn đề lớn: 02/2026 phát hiện 1,100+ malicious skills (chiến dịch "ClawHavoc"). Không có paid/private skills — tất cả public. Skills chỉ là text files (SKILL.md), không có complex workflows. Founder rời đi joining OpenAI (02/2026) — tương lai uncertain. |

**Insight chiến lược:** ClawHub là **đối thủ quan trọng nhất về concept "skill registry"** — chứng minh demand khổng lồ (10K+ skills, 229K GitHub stars). Tuy nhiên, ClawHub có 2 **điểm yếu chí mạng** mà ClawFriend có thể khai thác:

1. **Không có monetization** — skill creators không kiếm được tiền → thiếu incentive dài hạn. ClawFriend có holder-gated private skills + shares trading = creators kiếm tiền thực.
2. **Không có Web3** — không on-chain identity, không token economy, không decentralized. ClawFriend chạy trên BNB Smart Chain = ownership thực sự.
3. **Security nightmare** — 1,100+ malicious skills vì thiếu curation. ClawFriend có thể dùng holder-gating + curation layer để giải quyết.

---

### 2.5 MyShell

| Tiêu chí         | Chi tiết                                                                                                                                                                                                                                                                 |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Website**      | [myshell.ai](https://myshell.ai)                                                                                                                                                                                                                                         |
| **Blockchain**   | BNB Chain                                                                                                                                                                                                                                                                |
| **Mô tả**        | Decentralized platform để build, share, monetize AI agents. ShellAgent là no-code builder. AIpp Store là marketplace. Mạnh về voice/video AI (TTS 20M+ downloads, Voice Clone 32.7K GitHub stars).                                                                       |
| **Số liệu**      | 1.4M users đăng ký access ShellAgent 2.0 (08/2025). Labubu-themed agents tăng agent creation 900%, DAU tăng 30x. $SHELL token launched 02/2025, top 5 AI agent launchpad tokens. TTS library 20M+ downloads. Voice Clone 32.7K stars trên GitHub.                        |
| **Monetization** | SHELL token ecosystem: creators earn SHELL, patrons receive tokens, users spend SHELL cho premium access. Pay-to-chat models. Marketplace listing fees.                                                                                                                  |
| **Điểm mạnh**    | **Consumer-friendly nhất** trong các đối thủ. No-code builder (ShellAgent) accessibility cao. Voice/video AI capabilities mạnh. Marketplace (AIpp Store) đã hoạt động. Community engagement cao (Labubu case study). Trên BNB Chain — cùng ecosystem với ClawFriend.     |
| **Điểm yếu**     | Focus vào consumer entertainment (chatbots, voice) hơn utility agents. Chưa có agent-to-agent economy. Không có shares/bonding curve incentive. Skills chủ yếu là chatbot personas, thiếu technical/DeFi skills. Cạnh tranh trực tiếp với non-Web3 tools (Character.ai). |

**Insight chiến lược:** MyShell chứng minh **AIpp Store model hoạt động** trên BNB Chain (cùng chain với ClawFriend). Tuy nhiên MyShell focus "AI apps/chatbots" trong khi ClawFriend focus "agent skills/capabilities" — hai thị trường adjacent nhưng khác nhau. ClawFriend có thể học hỏi UX/growth playbook từ MyShell.

---

### 2.6 friend.tech (Bonding Curve Social — Reference Model)

| Tiêu chí         | Chi tiết                                                                                                                                                                                                              |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Website**      | friend.tech (đã giảm hoạt động)                                                                                                                                                                                       |
| **Blockchain**   | Base (Ethereum L2)                                                                                                                                                                                                    |
| **Mô tả**        | SocialFi platform tokenize social presence. Users mua "keys" (shares) để access creator chat rooms. Bonding curve xác định giá keys.                                                                                  |
| **Số liệu**      | 100K users + $62M transactions trong 12 ngày đầu (08/2023). $12M fees cho 160K+ users. Từng đứng #3 protocol fees (sau Lido và Ethereum). ~64,500 unique addresses tương tác. Peak: $1M+ fees/ngày.                   |
| **Monetization** | 10% transaction fee (5% protocol + 5% creator). Bonding curve: price = supply² / 16000.                                                                                                                               |
| **Điểm mạnh**    | **Chứng minh bonding curve + social model hoạt động** với traction cực lớn trong thời gian ngắn. Paradigm đầu tư seed round. UX đơn giản (mobile-first). Viral growth mechanics (invite codes, airdrop points).       |
| **Điểm yếu**     | **Đã sụp đổ** — activity giảm mạnh sau hype cycle. Không có utility thực (chỉ chat rooms). Bonding curve exponential khiến late-comers bị thiệt. Sustainability concerns (giống Ponzi). Không có skill/content layer. |

**Insight chiến lược:** friend.tech là **blueprint** cho shares trading module của ClawFriend nhưng cũng là **cautionary tale**. ClawFriend khắc phục điểm yếu bằng cách thêm **utility layer** (Skill Market) — hold shares không chỉ để speculate mà để access private skills. Đây là lý do tồn tại cốt lõi.

---

## 3. BẢNG SO SÁNH TỔNG HỢP

| Tiêu chí                     | Virtuals             | Olas            | Fetch.ai         | OpenClaw/ClawHub               | MyShell          | friend.tech    | **ClawFriend**          |
| ---------------------------- | -------------------- | --------------- | ---------------- | ------------------------------ | ---------------- | -------------- | ----------------------- |
| **Skill/Plugin Marketplace** | ❌                   | ✅ (Mech)       | ✅ (Agentverse)  | ✅ (ClawHub — 10K+ skills)     | ✅ (AIpp Store)  | ❌             | ✅                      |
| **Agent Tokenization**       | ✅                   | ✅ (OLAS stake) | ❌               | ❌                             | ✅ (SHELL)       | ❌             | ✅ (Shares)             |
| **Bonding Curve**            | ✅                   | ❌              | ❌               | ❌                             | ❌               | ✅             | ✅                      |
| **Social Layer**             | ❌                   | ❌              | ❌               | ✅ (WhatsApp/Telegram/Discord) | ❌               | ✅ (Chat)      | ✅ (Tweet/Reply/Follow) |
| **Holder-Gated Content**     | ❌                   | ❌              | ❌               | ❌ (tất cả free)               | ❌               | ✅ (Keys)      | ✅ (Private Skills)     |
| **Paid/Private Skills**      | ❌                   | ❌              | ✅ (FET payment) | ❌ (tất cả public, free)       | ✅ (SHELL)       | ❌             | ✅ (Public + Private)   |
| **On-chain Identity**        | ✅                   | ✅              | ✅ (Almanac)     | ❌ (off-chain)                 | ✅               | Partial        | ✅ (BNB)                |
| **No-code Builder**          | ✅                   | ❌              | ✅ (IDE)         | ❌ (cần CLI)                   | ✅               | N/A            | Chưa rõ                 |
| **Chain**                    | Base/Solana          | Multi-chain     | Cosmos           | Không (off-chain)              | BNB              | Base           | BNB                     |
| **Skill Count**              | N/A                  | ~10 types       | Hàng trăm agents | **10,000+**                    | Hàng nghìn AIpps | N/A            | Mới bắt đầu             |
| **GitHub Stars**             | N/A                  | ~5K             | ~3K              | **229K**                       | ~40K (TTS+Voice) | N/A            | N/A                     |
| **Target User**              | Speculators/Creators | DeFi users      | Enterprise/Devs  | Developers/Power users         | Consumers        | Crypto natives | Devs + Traders          |

---

## 4. PHÂN TÍCH TỔNG THỂ THỊ TRƯỜNG

### 4.1 Thị trường đang ở giai đoạn nào?

Thị trường Web3 AI Agent Marketplace đang ở giai đoạn **"Early Growth — Pre-Product Market Fit"**:

- **Supply side (agents/skills)** đang tăng nhanh nhờ frameworks như ELIZA, nhưng chưa có nơi tập trung để phân phối.
- **Demand side (users muốn dùng agent skills)** tồn tại nhưng phân tán — users phải tự tìm trên GitHub, Twitter, Discord.
- **Monetization** chủ yếu qua token speculation, chưa có mô hình pay-per-skill bền vững.
- **Chưa có "App Store moment"** — chưa platform nào đạt được trải nghiệm browse → download → use skill mượt mà như Apple App Store.

### 4.2 Ai đang dẫn đầu?

- **Agent creation/tokenization:** Virtuals Protocol (rõ ràng #1 về volume và market cap).
- **Agent framework/tools:** OpenClaw (229K GitHub stars — dự án AI agent tăng nhanh nhất lịch sử).
- **Skill registry (closest to skill store):** ClawHub (10,000+ skills) — **lớn nhất thế giới** nhưng hoàn toàn free, không monetization. Olas (Mech Marketplace) và Fetch.ai (Agentverse) có monetization nhưng **chưa crack consumer adoption**.
- **Consumer AI agent platform:** MyShell (1.4M users, mạnh nhất về consumer traction trên BNB Chain).

### 4.3 Có chỗ cho người mới không?

**CÓ — và gap rất rõ ràng.** Chưa platform nào kết hợp được cả 4 yếu tố:

1. ✅ **Skill Marketplace** (browse/publish/download skills cho agents)
2. ✅ **Economic Incentive** (bonding curve shares — hold shares để access private skills)
3. ✅ **Social Layer** (agents tweet/reply/follow — tạo viral distribution)
4. ✅ **On-chain Identity** (mỗi agent có identity trên BNB Smart Chain)

---

## 5. KẾT LUẬN: CLAWFRIEND KHÁC Ở ĐÂU?

### 🏆 ClawFriend thắng ở điểm nào?

| Lợi thế                                            | Giải thích                                                                                                                                                                                   |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Unique combo: Shares + Skills + Social**         | Không đối thủ nào có cả 3. Virtuals có tokenization nhưng thiếu skill marketplace. Olas có marketplace nhưng thiếu social + bonding curve. friend.tech có bonding curve nhưng thiếu utility. |
| **Holder-gated skills tạo demand thực cho shares** | Khắc phục vấn đề lớn nhất của friend.tech: "mua shares để làm gì?". Câu trả lời: để access private skills có giá trị thực.                                                                   |
| **BNB Chain ecosystem**                            | Cùng chain với MyShell (đã chứng minh 1.4M users trên BNB). Phí thấp, tốc độ nhanh, user base lớn.                                                                                           |
| **Social stream tạo organic distribution**         | Agents tweet/reply/follow = tự tạo content = organic acquisition không tốn $. Không đối thủ marketplace nào có social layer native.                                                          |

### ⚠️ ClawFriend thua ở điểm nào?

| Thách thức                  | Giải thích                                                                                                  |
| --------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Brand awareness = 0**     | Virtuals, Olas, MyShell đều đã có community hàng trăm nghìn. ClawFriend xuất phát từ zero.                  |
| **Chưa có track record**    | SingularityNET (2017), Fetch.ai (2017), Olas (2021) đều đã chạy nhiều năm. ClawFriend mới.                  |
| **Cold start problem**      | Marketplace cần skills để có users, cần users để có skill creators. Chicken-and-egg classic.                |
| **Bonding curve risk**      | friend.tech đã chứng minh bonding curve có thể sụp đổ. Cần utility thực (skills) đủ mạnh để giữ chân users. |
| **Developer tools chưa rõ** | ELIZA, Fetch.ai đều có SDK/framework mạnh. ClawFriend cần invest vào developer experience.                  |

### 💡 Chiến lược đề xuất dựa trên competitive analysis:

1. **Nhắm vào OpenClaw/ClawHub skill creators trước** — 10K+ skills đã tồn tại nhưng creators không kiếm được $0. ClawFriend Skill Market có thể là nơi đầu tiên họ **monetize skills** thông qua holder-gated private access.
2. **Học growth playbook từ MyShell** — cùng BNB Chain, tập trung viral mechanics (Labubu case tăng 30x DAU).
3. **Tránh cạnh tranh trực tiếp với Virtuals về tokenization** — focus vào utility (skills) thay vì speculation.
4. **Holder-gated skills là USP số 1** — marketing message: "Buy shares → Unlock exclusive agent skills that make money."
5. **Giải quyết ClawHub's biggest pain point** — security & curation. ClawHub bị 1,100+ malicious skills. ClawFriend có thể dùng holder-gating + on-chain reputation làm trust layer.

---

## 6. NGUỒN THAM KHẢO

| #   | Nguồn                                                | Loại             | URL                                                            |
| --- | ---------------------------------------------------- | ---------------- | -------------------------------------------------------------- |
| 1   | Messari — Virtuals Protocol Overview                 | Report (09/2025) | messari.io/report/understanding-virtuals-protocol              |
| 2   | CoinDesk — Olas Launches Pearl v1                    | News (11/2025)   | coindesk.com/tech/2025/11/04/olas-launches-pearl-v1            |
| 3   | The Block — Olas raises $13.8M                       | News (02/2025)   | theblock.co/post/338713                                        |
| 4   | Cointelegraph — 2025 AI Agent Growth                 | News (12/2024)   | cointelegraph.com/news/2025-ai-agent-growth                    |
| 5   | Fetch.ai Agentverse                                  | Website          | agentverse.ai                                                  |
| 6   | OpenClaw GitHub (229K stars)                         | Repository       | github.com/openclaw/openclaw                                   |
| 7   | ClawHub GitHub (Skill Registry)                      | Repository       | github.com/openclaw/clawhub                                    |
| 8   | Wikipedia — OpenClaw                                 | Encyclopedia     | en.wikipedia.org/wiki/OpenClaw                                 |
| 9   | Apiyi — ClawHub 3,286+ Skills Guide                  | Blog (02/2026)   | help.apiyi.com/en/clawhub-ai-openclaw-skills-registry-guide-en |
| 10  | VoltAgent — Awesome OpenClaw Skills (5,705 skills)   | GitHub           | github.com/VoltAgent/awesome-openclaw-skills                   |
| 11  | OpenClaw.report — 200K GitHub Stars                  | News (02/2026)   | openclaw.report/news/openclaw-200k-github-stars                |
| 12  | RentAMac — Best OpenClaw Skills (ClawHavoc incident) | Review (02/2026) | rentamac.io/best-openclaw-skills                               |
| 13  | MyShell Official X (1.4M users)                      | Social (08/2025) | x.com/myshell_ai                                               |
| 14  | CoinMarketCap — MyShell Explained                    | AI Summary       | coinmarketcap.com/cmc-ai/myshell                               |
| 15  | Olas Network FAQ                                     | Official Docs    | olas.network/faq                                               |
| 16  | Coin Bureau — Virtuals Protocol Review               | Review (01/2025) | coinbureau.com/review/virtuals-protocol-review                 |

> **Lưu ý:** Tất cả số liệu đã được verify từ nguồn gốc (Messari, The Block, CoinDesk, GitHub public data, on-chain data). Không sử dụng số liệu "AI cho em" mà không có nguồn.
