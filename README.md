<div align="center">

# 📐 System Design Notes

### My personal notes while learning system design — weekly practice

[![Study](https://img.shields.io/badge/Currently_Reading-System_Design_Interview_Alex_Xu-blue?style=flat-square)](https://www.amazon.in/System-Design-Interview-Insiders-Guide/dp/B08CMF2CQF)
[![YouTube](https://img.shields.io/badge/Watching-ByteByteGo-red?style=flat-square&logo=youtube)](https://youtube.com/@ByteByteGo)

</div>

---

## 🎯 What This Repo Contains

My personal notes, diagrams, and practice designs while learning system design. Updated every week.

---

## 📚 Resources I'm Using

| Resource | Type | Status |
|----------|------|--------|
| System Design Interview - Alex Xu | Book | 🔄 Reading |
| ByteByteGo YouTube | Videos | 🔄 Watching weekly |
| Designing Data-Intensive Apps | Book | ⏳ Next |
| highscalability.com | Articles | 🔄 Weekly |

---

## 🗂️ Topics Covered

### Core Concepts
- [ ] Load Balancing
- [ ] Caching (Redis, CDN)
- [ ] Database Scaling (sharding, replication)
- [ ] Message Queues (Kafka, RabbitMQ)
- [ ] CAP Theorem
- [ ] SQL vs NoSQL

### Practice Designs
- [ ] URL Shortener (bit.ly)
- [ ] Chat Application (WhatsApp)
- [ ] Twitter Feed
- [ ] YouTube
- [ ] Uber
- [ ] Instagram
- [ ] Amazon E-commerce
- [ ] Google Search

---

## 📝 Notes Structure

```
system-design-notes/
│
├── concepts/
│   ├── load-balancing.md
│   ├── caching.md
│   ├── databases.md
│   └── message-queues.md
│
├── designs/
│   ├── url-shortener.md
│   ├── chat-app.md
│   └── ...
│
└── README.md
```

---

## 💡 The Framework I Use

For every system design question:

```
1. CLARIFY (5 min)
   → How many users?
   → Read heavy or write heavy?
   → What features exactly?

2. ESTIMATE (5 min)
   → Requests per second
   → Storage needed
   → Bandwidth

3. HIGH LEVEL (10 min)
   → Client → Load Balancer → Servers → DB
   → Draw simple boxes first

4. DEEP DIVE (15 min)
   → Database design
   → API design
   → Caching strategy

5. BOTTLENECKS (10 min)
   → What breaks first?
   → How to fix it?
```

---

<div align="center">

Learning in public. Updated every weekend.

</div>
