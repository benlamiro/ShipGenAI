<div align="center">

<a href="https://shipgenai.org">
  <img src="https://img.shields.io/badge/🌐_Website-shipgenai.org-006994?style=for-the-badge&labelColor=003D5C" alt="ShipGenAI Website">
</a>

<br/><br/>

# 🚀 ShipGenAI

### *50 production-ready Generative AI SaaS apps — brand them, ship them, keep 100% of the revenue.*

<p>
  <a href="https://shipgenai.org"><strong>shipgenai.org</strong></a> ·
  <a href="#-quick-start">Quick Start</a> ·
  <a href="#-open-source-ai-platforms">Platforms</a> ·
  <a href="#-image-generation">Image</a> ·
  <a href="#-video-generation">Video</a> ·
  <a href="#-beauty--fashion-ai">Beauty & Fashion</a> ·
  <a href="#-e-commerce--product-photography">E-commerce</a>
</p>

<p>
  <a href="https://github.com/benlamiro/ShipGenAI/stargazers">
    <img src="https://img.shields.io/github/stars/benlamiro/ShipGenAI?style=for-the-badge&logo=github&color=FFD700" alt="Stars">
  </a>
  <a href="https://github.com/benlamiro/ShipGenAI/network/members">
    <img src="https://img.shields.io/github/forks/benlamiro/ShipGenAI?style=for-the-badge&logo=github&color=4FC3F7" alt="Forks">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/github/license/benlamiro/ShipGenAI?style=for-the-badge&color=8B5CF6" alt="MIT License">
  </a>
  <img src="https://img.shields.io/github/last-commit/benlamiro/ShipGenAI?style=for-the-badge&color=F97316" alt="Last Commit">
</p>

<p>
  <img src="https://img.shields.io/badge/Stripe_Billing-635BFF?style=flat-square&logo=stripe&logoColor=white" alt="Stripe">
  <img src="https://img.shields.io/badge/Google_OAuth-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google OAuth">
  <img src="https://img.shields.io/badge/One--click_Vercel_Deploy-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/MIT_Licensed-22C55E?style=flat-square" alt="MIT">
  <img src="https://img.shields.io/badge/50+_AI_Apps-FF6B6B?style=flat-square" alt="50+ Apps">
</p>

</div>

---

## 💡 What is ShipGenAI?

**[ShipGenAI](https://shipgenai.org)** is a curated collection of **50 complete, production-ready AI SaaS products** you can launch under your own brand — this weekend.

Each app ships with:
- 💳 **Stripe checkout + webhooks** — credit-based billing, webhook confirmation, automatic credit deduction
- 🔐 **Google OAuth** — zero auth to build or maintain
- 🤖 **100+ AI models** via [MuAPI](https://muapi.ai) — swap models without touching app code; handles async polling, retries, and failover
- 🌐 **Vercel-ready** — one-click deploy to global CDN
- 🗄️ **Prisma + PostgreSQL** — users, credits, and job history out of the box
- 🆓 **MIT licensed** — sell it, white-label it, charge whatever you want

> **Explore all apps → [shipgenai.org](https://shipgenai.org)**

---

## 💰 The Business Case

These are not demos or UI kits — they are **complete, sellable SaaS products**.

| | Example: AI Headshot Generator |
|---|---|
| **You charge users** | $29 for a pack of 10 headshots |
| **AI cost per pack** | ~$1.50 (via MuAPI) |
| **Your margin** | ~$27.50 per pack (~95%) |
| **At 100 customers/month** | ~$2,750 MRR |
| **At 500 customers/month** | ~$13,750 MRR |

> AI headshot tools charge $29–$49/pack. Virtual staging tools charge $29/image. Video clipping tools charge $49/month. Companies built on these exact ideas are doing **millions in revenue** — the open-source version is right here.

---

## 🚀 Quick Start

```bash
# 1. Clone the template you want
git clone https://github.com/SamurAIGPT/<template-name>
cd <template-name>

# 2. Set up environment variables
cp .env.example .env
# Fill in: DATABASE_URL, NEXTAUTH_SECRET, GOOGLE_CLIENT_ID/SECRET,
#          STRIPE_SECRET_KEY, STRIPE_WEBHOOK_SECRET, MUAPI_API_KEY

# 3. Initialize DB and start
npx prisma db push && npm run dev
```

Or hit the **Deploy to Vercel** button in each template's README for instant live deployment.

---

## 📑 Table of Contents

- [🌐 Open-Source AI Platforms](#-open-source-ai-platforms)
- [🖼️ Image Generation](#-image-generation)
- [🎬 Video Generation](#-video-generation)
- [💄 Beauty & Fashion AI](#-beauty--fashion-ai)
- [🛒 E-commerce & Product Photography](#-e-commerce--product-photography)
- [🏠 Home & Real Estate AI](#-home--real-estate-ai)
- [👤 Portrait & Avatar AI](#-portrait--avatar-ai)
- [✍️ Writing & Content](#️-writing--content)
- [🤖 AI Agents & Chatbots](#-ai-agents--chatbots)
- [🎵 Audio & Voice](#-audio--voice)
- [🔧 Platform Integrations](#-platform-integrations)

---

## 🌐 Open-Source AI Platforms

Full-stack platforms you can self-host or white-label. Leonardo AI charges $12–$60/mo. OpenArt charges $9–$57/mo. Krea charges $10–$35/mo. These open-source alternatives capture that same revenue with zero licensing fees.

| App | Description | Competing With | Stars |
|---|---|---|---|
| [Open Generative AI](./platforms/Open-Generative-AI) · [↗ GitHub](https://github.com/Anil-matcha/Open-Generative-AI) | Open-source AI image & video studio with 200+ models. No content filters. Self-hosted. | Leonardo AI ($60/mo), Krea ($35/mo) | ⭐ 20k+ |
| [Free AI Social Media Scheduler](./platforms/Free-AI-Social-Media-Scheduler) · [↗ GitHub](https://github.com/Anil-matcha/Free-AI-Social-Media-Scheduler) | Self-hostable AI social media scheduler with built-in content generation | Buffer ($18/mo), Hootsuite ($99/mo) | ⭐ 420 |
| [Open AI Design Agent](./platforms/Open-AI-Design-Agent) · [↗ GitHub](https://github.com/Anil-matcha/Open-AI-Design-Agent) | Autonomous multi-step AI design agent for creatives and brand kits | Lovart AI ($30/mo), Galileo AI ($50/mo) | ⭐ 807 |
| [Open Poe AI](./platforms/Open-Poe-AI) · [↗ GitHub](https://github.com/Anil-matcha/Open-Poe-AI) | Self-hosted multi-model AI chat — GPT, Claude, Gemini, Llama | Poe AI ($20/mo), ChatGPT Plus ($20/mo) | ⭐ 241 |

---

## 🖼️ Image Generation

**The market:** Midjourney makes est. $200M+/year. DALL·E powers ChatGPT Plus for 200M+ users. Aragon AI (just headshots) reportedly crossed $1M ARR. One niche image product = real income.

| Template | Description | Competing With | Demo |
|---|---|---|---|
| [Nano Banana Generator](./image_generation/nano-banana-generator) · [↗ GitHub](https://github.com/SamurAIGPT/nano-banana-generator) | Text-to-image and multi-image reference editing SaaS | Midjourney ($10–$30/mo), DALL·E ($15/mo) | [Demo](https://nano-banana-generator.vercel.app/) |
| [AI Headshot Generator](./image_generation/ai-headshot-generator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-headshot-generator) | LinkedIn photos, team portraits, personal branding | Aragon AI ($29–$49/pack) — est. $1M+ ARR | [Demo](https://ai-headshot-generator.vercel.app/) |
| [AI Logo Studio](./image_generation/ai-logo-studio) · [↗ GitHub](https://github.com/SamurAIGPT/ai-logo-studio) | Text-to-logo and sketch-to-logo brand identity generator | Looka ($20–$80/logo), Brandmark ($25–$65/logo) | [Demo](https://ai-logo-studio.vercel.app/) |
| [AI Meme Studio](./image_generation/ai-meme-generator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-meme-generator) | AI meme & viral short video generator with multiple models | Imgflip Pro ($10/mo), Supermeme ($19/mo) | [Demo](https://ai-meme-generator.vercel.app/) |
| [Old Photo Restore](./image_generation/old-photo-restore) · [↗ GitHub](https://github.com/SamurAIGPT/old-photo-restore) | Colorize, denoise, and repair damaged vintage photos | Remini (est. $100M+ revenue), MyHeritage ($50/yr) | [Demo](https://old-photo-restore.vercel.app/) |
| [ClearMark AI](./image_generation/clearmark-ai) · [↗ GitHub](https://github.com/SamurAIGPT/clearmark-ai) | Remove watermarks, logos, and text overlays using GPT Image 2 | Watermarkremover.io ($9.99/mo), HitPaw ($20/mo) | [Demo](https://clearmark-ai.vercel.app/) |

---

## 🎬 Video Generation

**The market:** Opus Clip hit $20M+ ARR. Runway raised $236M. The AI video tools market is projected at $2B+ by 2027. Clipping and short-form tools are the highest-demand entry point.

| Template | Description | Competing With | Demo |
|---|---|---|---|
| [Seedance 2 Generator](./video_generation/seedance-2-generator) · [↗ GitHub](https://github.com/SamurAIGPT/seedance-2-generator) | Text-to-video and multi-image reference video SaaS | Runway ($12–$76/mo), Kling ($10–$36/mo) | [Demo](https://seedance-2-generator.vercel.app/) |
| [Veo Video Generator](./video_generation/veo4-video-generator) · [↗ GitHub](https://github.com/SamurAIGPT/veo4-video-generator) | Text-to-video and image-to-video with Google Veo | Sora ($20/mo), Runway ($76/mo) | [Demo](https://veo4-video-generator.vercel.app/) |
| [AI Kissing Video Generator](./video_generation/ai-kissing-video-generator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-kissing-video-generator) | Merge two portraits into a romantic AI video using Veo 3 & Gemini Omni | Reface ($4.99/mo) | [Demo](https://ai-kissing-video-generator-amber.vercel.app/) |
| [AI Youtube Shorts Generator](./video_generation/AI-Youtube-Shorts-Generator) · [↗ GitHub](https://github.com/SamurAIGPT/AI-Youtube-Shorts-Generator) | Auto-extract viral 9:16 shorts from long-form videos | Opus Clip ($15–$49/mo, est. $20M+ ARR) | — |
| [AI Clipping Generator](./video_generation/ai-clipping-generator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-clipping-generator) | Auto-extract Reels and TikToks from YouTube videos | Opus Clip ($15–$49/mo), SubMagic ($20–$60/mo) | [Demo](https://ai-clipping-generator.vercel.app/) |
| [AI Micro-Drama Generator](./video_generation/Open-AI-Micro-Drama-Generator) · [↗ GitHub](https://github.com/Anil-matcha/Open-AI-Micro-Drama-Generator) | Turn any idea into a complete short-form AI drama | Creatify ($39/mo), Synthesia ($22–$67/mo) | — |
| [AI B-Roll Generator](https://github.com/Anil-matcha/AI-B-roll) | Auto-generate relevant B-roll footage from scripts or transcripts | Storyblocks ($15/mo), Artlist ($16/mo) | — |
| [Open AI UGC](./video_generation/Open-AI-UGC) · [↗ GitHub](https://github.com/Anil-matcha/Open-AI-UGC) | Generate AI UGC-style video ads with virtual creators | Arcads ($99–$299/mo), MakeUGC ($49/mo) | — |

---

## 💄 Beauty & Fashion AI

**The market:** ModiFace (acquired by L'Oreal for est. $68M) powers virtual try-ons for major retailers. YouCam makes $50M+/year. Beauty AI has some of the highest consumer willingness-to-pay.

| Template | Description | Competing With | Demo |
|---|---|---|---|
| [TryOn AI](./beauty_fashion/ai-tryon) · [↗ GitHub](https://github.com/SamurAIGPT/ai-tryon) | Fit any garment onto any person photo | Botika ($99+/mo for brands), Lalaland.ai (enterprise) | [Demo](https://ai-tryon-smoky.vercel.app/) |
| [AI Hairstyle Simulator](./beauty_fashion/ai-hair-style-simulator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-hair-style-simulator) | Virtual hair makeover and color try-on | YouCam Hair ($30/yr), HairStyle.ai ($7.99/mo) | [Demo](https://ai-hair-style-simulator.vercel.app/) |
| [AI Tattoo Try-On](./beauty_fashion/ai-tattoo-try-on) · [↗ GitHub](https://github.com/SamurAIGPT/ai-tattoo-try-on) | Preview tattoo designs on skin virtually | Ink Hunter (1M+ users), Tattoosmart ($4.99/mo) | [Demo](https://ai-tattoo-try-on.vercel.app/) |
| [AI Professional Makeup](./beauty_fashion/ai-professional-makeup-generator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-professional-makeup-generator) | Try on professional makeup looks with AI | YouCam Makeup ($30/yr), Perfect Corp (enterprise) | [Demo](https://ai-professional-makeup-generator.vercel.app/) |

---

## 🛒 E-commerce & Product Photography

**The market:** Photoroom raised $19M Series A and reportedly crossed $50M ARR. E-commerce sellers pay premium for anything that speeds up product listings — a high-LTV B2B niche.

| Template | Description | Competing With | Demo |
|---|---|---|---|
| [Resale Photo Enhancer](./ecommerce/resale-photo-enhancer) · [↗ GitHub](https://github.com/SamurAIGPT/resale-photo-enhancer) | AI product photo studio for eBay, Poshmark, Depop sellers | Photoroom ($9.99–$79/mo, est. $50M+ ARR) | [Demo](https://resale-photo-enhancer.vercel.app/) |
| [Amazon Product Studio](./ecommerce/amazon-product-studio) · [↗ GitHub](https://github.com/SamurAIGPT/amazon-product-studio) | Generate studio-quality product photos from reference images | Flair AI ($38/mo), Pebblely ($19/mo) | [Demo](https://amazon-product-studio.vercel.app/) |

---

## 🏠 Home & Real Estate AI

**The market:** Virtual staging companies charge $25–$75 per room. Rooomy raised $5M. Zillow reports staged homes sell 73% faster.

| Template | Description | Competing With | Demo |
|---|---|---|---|
| [AI Virtual Staging](./home_real_estate/ai-virtual-staging) · [↗ GitHub](https://github.com/SamurAIGPT/ai-virtual-staging) | Furnish empty rooms with photorealistic AI furniture | Rooomy ($25–$75/room), Stuccco ($29/room) | [Demo](https://ai-virtual-staging.vercel.app/) |
| [AI Room Redesign](./home_real_estate/ai-room-redesign) · [↗ GitHub](https://github.com/SamurAIGPT/ai-room-redesign) | Transform any room into a new style or aesthetic | Reimagine Home ($15/mo), AI Room Planner ($15/mo) | [Demo](https://ai-room-redesign.vercel.app/) |
| [AI Room Declutter](./home_real_estate/ai-room-declutter) · [↗ GitHub](https://github.com/SamurAIGPT/ai-room-declutter) | Transform messy rooms into photorealistic clean interiors | Virtually Staging Properties ($25/room) | [Demo](https://ai-room-declutter.vercel.app/) |
| [AI Architecture Visualizer](./home_real_estate/ai-architecture-visualizer) · [↗ GitHub](https://github.com/SamurAIGPT/ai-architecture-visualizer) | Turn floor plans into photorealistic 3D renders | Foyr Neo ($49/mo), Cedreo ($79/mo) | [Demo](https://ai-architecture-visualizer.vercel.app/) |

---

## 👤 Portrait & Avatar AI

**The market:** Lensa AI made $50M+ in a single month from the avatar feature launch. Avatar tools consistently rank among the highest-revenue consumer AI apps.

| Template | Description | Competing With | Demo |
|---|---|---|---|
| [AI Character Studio](./portrait_avatar/ai-character-studio) · [↗ GitHub](https://github.com/SamurAIGPT/ai-character-studio) | Generate custom AI character portraits and chat with them | Character.ai (est. $200M+ ARR), Replika ($7.99/mo) | [Demo](https://ai-character-studio-beta.vercel.app/) |
| [AI Profile Picture](./portrait_avatar/ai-profile-picture) · [↗ GitHub](https://github.com/SamurAIGPT/ai-profile-picture) | Generate stunning profile pictures with AI style transfer | PFPMaker ($10/mo), ProfilePicture.ai ($12/pack) | [Demo](https://ai-profile-picture.vercel.app/) |
| [AI Baby Generator](./portrait_avatar/ai-baby-generator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-baby-generator) | Predict what your baby will look like using two parent photos | BabyGenerator.io ($3.99/use), MakeMeBabies.com | [Demo](https://ai-baby-generator.vercel.app/) |
| [AI Cartoon Generator](./portrait_avatar/ai-cartoon-generator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-cartoon-generator) | Turn any photo into cartoon, anime, or illustrated style | ToonMe (40M+ users), Cartoon.ai ($9.99/mo) | [Demo](https://ai-cartoon-generator.vercel.app/) |

---

## ✍️ Writing & Content

**The market:** Jasper AI raised $125M at a $1.5B valuation. Copy.ai surpassed $10M ARR. WriteSonic crossed $10M ARR.

| Template | Description | Competing With | Demo |
|---|---|---|---|
| [AI Blog Writer](./writing_content/ai-blog-writer) · [↗ GitHub](https://github.com/SamurAIGPT/ai-blog-writer) | Long-form SEO blog posts with outline, research, and publish | Jasper ($49/mo), Writesonic ($19/mo) | [Demo](https://ai-blog-writer.vercel.app/) |
| [AI Email Writer](./writing_content/ai-email-writer) · [↗ GitHub](https://github.com/SamurAIGPT/ai-email-writer) | Cold emails, sequences, and reply drafting with AI | Lavender ($29/mo), Regie.ai ($39/mo) | [Demo](https://ai-email-writer.vercel.app/) |
| [AI Resume Builder](./writing_content/ai-resume-builder) · [↗ GitHub](https://github.com/SamurAIGPT/ai-resume-builder) | AI-powered resume creation, optimization, and tailoring | Teal ($29/mo), Kickresume ($10/mo) | [Demo](https://ai-resume-builder.vercel.app/) |
| [AI Voice Cloner](./writing_content/ai-voice-cloner) · [↗ GitHub](https://github.com/SamurAIGPT/ai-voice-cloner) | Clone any voice from a short sample and generate speech | ElevenLabs ($5–$99/mo, est. $80M+ ARR) | [Demo](https://ai-voice-cloner.vercel.app/) |
| [AI Podcast Generator](./writing_content/ai-podcast-generator) · [↗ GitHub](https://github.com/SamurAIGPT/ai-podcast-generator) | Turn any text or topic into a ready-to-publish podcast episode | Wondercraft ($29/mo), Podcastle ($14/mo) | [Demo](https://ai-podcast-generator.vercel.app/) |

---

## 🤖 AI Agents & Chatbots

**The market:** Intercom crossed $400M ARR. Drift was acquired for $800M. Enterprise chatbot market projected at $27B by 2030.

| Template | Description | Competing With | Demo |
|---|---|---|---|
| [AI Customer Support](./ai_agents/ai-customer-support) · [↗ GitHub](https://github.com/SamurAIGPT/ai-customer-support) | Custom AI chatbot trained on your docs and website | Intercom ($74/mo), Drift (enterprise) | [Demo](https://ai-customer-support.vercel.app/) |
| [AI Sales Agent](./ai_agents/ai-sales-agent) · [↗ GitHub](https://github.com/SamurAIGPT/ai-sales-agent) | Autonomous AI that qualifies leads and books meetings | 6sense (enterprise), Conversica (enterprise) | [Demo](https://ai-sales-agent.vercel.app/) |
| [Open Poe AI](./platforms/Open-Poe-AI) · [↗ GitHub](https://github.com/Anil-matcha/Open-Poe-AI) | Self-hosted multi-model AI chat — GPT, Claude, Gemini, Llama | Poe AI ($20/mo), ChatGPT Plus ($20/mo) | — |

---

## 🔧 Platform Integrations

| Template | Description | Stars |
|---|---|---|
| [ChatGPT for Slack](./platforms/chatgpt-slack) · [↗ GitHub](https://github.com/Anil-matcha/ChatGPT-Slack-Bot) | ChatGPT Slack bot with memory, file support, and team context | ⭐ 305 |
| [ChatGPT for Discord](./platforms/chatgpt-discord) · [↗ GitHub](https://github.com/Anil-matcha/ChatGPT-Discord-Bot) | Full ChatGPT bot for Discord with slash commands and threads | ⭐ 565 |
| [ChatGPT for Teams](./platforms/chatgpt-teams) · [↗ GitHub](https://github.com/Anil-matcha/ChatGPT-Teams-Bot) | Enterprise Microsoft Teams bot with GPT-4 and file parsing | ⭐ 104 |
| [ChatGPT for Website](./platforms/chatgpt-website) · [↗ GitHub](https://github.com/Anil-matcha/ChatGPT-Website-Widget) | Embeddable ChatGPT widget for any website | ⭐ 1.1k |

---

## 🛠️ Tech Stack

Every template in this collection uses the same proven stack:

| Layer | Technology |
|---|---|
| **Frontend** | Next.js 14+ (App Router), TypeScript, Tailwind CSS |
| **Auth** | NextAuth.js + Google OAuth |
| **Database** | PostgreSQL + Prisma ORM |
| **Payments** | Stripe Checkout + Webhooks |
| **AI Models** | [MuAPI](https://muapi.ai) — 100+ models, async polling, failover |
| **Deployment** | Vercel — one-click, global CDN |

---

## 🤝 Contributing

Found a new AI SaaS template worth adding? Open a PR! We welcome:
- New complete SaaS templates with billing + auth
- Improvements to existing template READMEs
- Additional niche categories

---

## 📄 License

MIT © [ShipGenAI](https://shipgenai.org) — fork it, brand it, sell it, keep everything.

---

<div align="center">

**Built for indie founders who want to ship fast and own their revenue.**

<a href="https://shipgenai.org">
  <img src="https://img.shields.io/badge/🚀_Explore_All_Apps-shipgenai.org-006994?style=for-the-badge&labelColor=003D5C" alt="Visit ShipGenAI">
</a>

<br/><br/>

<sub>⭐ Star this repo to stay updated — new apps added regularly.</sub>

</div>
