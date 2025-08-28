# Support Agent Testing

A full-screen Dify chatbot testing interface ready for production deployment.

## 🚀 Quick Deploy to Vercel

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. **Deploy from this folder**:
   ```bash
   cd support-agent-testing
   vercel --prod
   ```

3. **Follow prompts**:
   - Set up and deploy? **Y**
   - Which scope? **Your account**
   - Project name? **support-agent-testing** (or custom name)
   - Directory? **Leave blank** (current directory)
   - Override settings? **N**

4. **Done!** You'll get a live URL like: `https://support-agent-testing.vercel.app`

## 📁 Files:

- **`index.html`** - Main full-screen chatbot interface (Vercel entry point)
- **`dify-test.html`** - Alternative bubble version
- **`dify-fullscreen.html`** - Same as index.html (backup)
- **`test.yml`** - Dify workflow configuration
- **`vercel.json`** - Deployment configuration
- **`package.json`** - Project metadata

## 🧪 Test Categories:

- **📦 Product questions** → Knowledge retrieval + LLM processing
- **🚚 Logistics questions** → Returns "Sorry, I don't know" 
- **❓ Other questions** → Returns "Sorry, I don't know"

## ✨ Features:

- **Full-screen interface** - Professional appearance
- **Mobile responsive** - Works on all devices
- **Loading animations** - Smooth user experience
- **Zero dependencies** - Pure HTML/CSS/JS
- **Vercel optimized** - Fast global delivery

## 🛠 Local Development:

```bash
# Start local server
python3 -m http.server 8000

# Or use npm script
npm run dev

# Access at: http://localhost:8000
```

## ⚙️ Configuration:

- **Dify Token**: `DtQK1IKVDcOrhElP`
- **Models**: Gemini 2.5 Flash + Cohere reranking
- **Knowledge Base**: `vJ+yg0Be+/+xA09J1Gq9fvzGNgTkL80Fu0sDtfcPLKBnf9MlhFLAyshrVegBgI2c`
- **Endpoint**: `https://udify.app/chatbot/DtQK1IKVDcOrhElP`

## 📝 Deployment Notes:

- **No build step required** - Static HTML site
- **Automatic HTTPS** - Vercel provides SSL
- **Global CDN** - Fast loading worldwide
- **Custom domains** - Add your own domain in Vercel dashboard