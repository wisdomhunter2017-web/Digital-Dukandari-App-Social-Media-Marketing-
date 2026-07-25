# Digital Dukandari - Auto Social Media Marketing System

Yeh repository **Digital Dukandari App** ke liye fully automated Social Media Marketing system hai.

### System Kya Karta Hai?

Aap sirf scripts, captions aur hooks add karte ho. Baaki kaam system khud karta hai:

- Diye hue time pe automatically content generate karta hai
- Short Reels + Long Videos banata hai
- Captions aur Hooks automatically lagata hai
- Images generate karta hai
- Facebook, Instagram, TikTok, YouTube, LinkedIn, Twitter/X aur WhatsApp pe schedule karke post karta hai

Yeh sab **n8n** ke through hota hai (self-hosted, free).

---

## Folder Structure

```
Digital-Dukandari-App-Social-Media-Marketing-/
├── scripts/
│   ├── 15-seconds/     # Short Reels (TikTok, Instagram Reels, YouTube Shorts)
│   ├── 30-seconds/     # Medium length content
│   └── long/           # Long form videos (YouTube, Facebook)
├── captions/           # Platform-wise captions
└── hooks/              # Attention grabbing hooks
```

Aap isme jitni marzi scripts, captions aur hooks add kar sakte ho. System unhe use karke automatically content banayega.

---

## Supported Platforms

- Instagram (Reels + Feed Posts)
- TikTok
- Facebook (Reels + Posts)
- YouTube (Shorts + Long Videos)
- LinkedIn
- Twitter / X
- WhatsApp (Status + Broadcast)

---

## How The System Works

1. **Content Library**
   - Aap `scripts/`, `captions/` aur `hooks/` folders mein content daalte ho
   - Jitna content chaho utna add kar sakte ho

2. **Auto Generation (n8n)**
   - System diye hue time pe khud script uthata hai
   - Caption + Hook jodta hai
   - AI se Image / Video / Reel generate karta hai
   - Best time calculate karta hai

3. **Auto Posting & Scheduling**
   - Har platform ke liye alag schedule
   - Calendar system se weekly / monthly planning
   - Fully automatic posting

---

## Quick Start

### 1. Repo Clone Karo
```bash
git clone https://github.com/wisdomhunter2017-web/Digital-Dukandari-App-Social-Media-Marketing-.git
cd Digital-Dukandari-App-Social-Media-Marketing-
```

### 2. Content Add Karo
- `scripts/15-seconds/` mein short scripts daalo
- `scripts/30-seconds/` mein medium scripts daalo
- `scripts/long/` mein long scripts daalo
- `captions/` aur `hooks/` mein related content daalo

### 3. n8n Setup Karo (Free)
- n8n self-hosted deploy karo (Render / Railway free tier)
- Social media nodes + AI nodes (Gemini / Groq) connect karo

### 4. Automation Start Karo
n8n workflow banayein jo:
- Scheduled time pe chale
- Script + Caption + Hook uthaye
- Image/Video generate kare
- Sab platforms pe post / schedule kare

---

## Content Strategy for Digital Dukandari

- **Week 1**: Awareness Campaign
- **Week 2**: Feature Spotlight
- **Week 3**: User Generated Content & Testimonials
- **Week 4**: Offers + Strong Call-to-Action

---

## Roadmap

- [x] Folder Structure
- [x] README
- [ ] Sample Scripts & Captions
- [ ] n8n Workflow Templates
- [ ] AI Image & Video Generation
- [ ] Multi-Platform Auto Scheduling
- [ ] Performance Tracking Dashboard

---

**Made with ❤️ for Digital Dukandari**
