# 🎯 Habit Coach Frontend

> Build consistent habits with AI-powered coaching  
> **Aariyatech UK Community Project**

---

## ✨ Features

- 📊 **Dashboard** - Track habits with real-time progress
- 💡 **AI Suggest** - Get personalized recommendations
- 📋 **AI Plan** - Set daily goals and commitments
- 💭 **AI Reflect** - Review progress with insights
- 📈 **Analytics** - View detailed statistics
- 🎨 **Responsive** - Works on all devices

---

## 🚀 Quick Start

**Prerequisites:** Node.js 16+

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) 🎉

---

## 📁 Project Structure

```
src/app/
├── layout.js              # Main wrapper
├── page.js               # Dashboard home
├── globals.css           # All styles
├── suggest/page.js       # Suggest page
├── plan/page.js          # Plan page
├── reflect/page.js       # Reflect page
├── analytics/page.js     # Analytics page
└── settings/page.js      # Settings page
```

---

## 🧭 Routes

File structure = URL routes in Next.js:

| File | Route |
|------|-------|
| `page.js` | `/` |
| `suggest/page.js` | `/suggest` |
| `plan/page.js` | `/plan` |
| `reflect/page.js` | `/reflect` |

---

## 🎨 Styling

Pure CSS (no frameworks) - easy to extend and learn!

---

## 📝 Available Commands

```bash
npm run dev      # Development server
npm run build    # Production build
npm start        # Start production server
npm run lint     # Run linter
```

---

## 🤝 Contributing

1. Fork the main repo
2. Create a branch: `git checkout -b feat/your-feature`
3. Make changes and test: `npm run dev`
4. Commit: `git commit -m "feat: description"`
5. Push and open a PR

**Good first tasks:**
- Enhance UI pages
- Add form validation
- Add tests
- Improve responsive design

---

## 🔗 Connect to Backend

Replace mock data with API calls:

```javascript
// src/app/lib/api.js
const API_BASE = process.env.NEXT_PUBLIC_API_URL || 'http://localhost:5000/api';

export async function getHabits() {
  const response = await fetch(`${API_BASE}/habits`);
  return response.json();
}
```

---

## 🗺️ Roadmap

- ✅ MVP dashboard
- 📌 Backend API integration
- 📌 User authentication
- 📌 Mobile app
- 📌 Dark mode

---

## 📚 Resources

- [Next.js Docs](https://nextjs.org/docs)
- [React Docs](https://react.dev)
- [MDN Web Docs](https://developer.mozilla.org/)

---

## 📞 Help

- [GitHub Issues](https://github.com/Aariyatech-UK/ai-community-hub/issues)
- [GitHub Discussions](https://github.com/Aariyatech-UK/ai-community-hub/discussions)

---

## 📄 License

ISC

---

**Happy coding! 🚀**
