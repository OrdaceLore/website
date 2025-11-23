# Cloudflare Worker - Hello World

A simple Cloudflare Worker application that returns a response with time information.

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Cloudflare account

### Installation

1. **Install dependencies:**
   ```bash
   cd page
   npm install
   ```

2. **Login to Cloudflare:**
   ```bash
   npx wrangler login
   ```

3. **Run locally:**
   ```bash
   npm run dev
   ```

4. **Deploy to Cloudflare:**
   ```bash
   npm run deploy
   ```

## 📁 Project Structure

```
.
├── page/
│   ├── src/
│   │   └── worker.js      # Main worker file
│   ├── package.json       # Dependencies
│   └── wrangler.jsonc     # Cloudflare configuration
└── README.md
```

## 🔧 Configuration

The worker configuration is in `page/wrangler.jsonc`. You can customize:
- Worker name
- Compatibility date
- Observability settings

## 📝 Notes

- The worker returns a simple text response with time information
- Deployed using Cloudflare Workers
- Uses Wrangler CLI for deployment

