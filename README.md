# Graduation Donation Page

A beautiful, responsive donation page for graduation expenses.

## 🚀 Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/kiannaquines/donation-page)

### Quick Deploy Steps:

1. **Push to GitHub** (if not already done):
   ```bash
   git add .
   git commit -m "Make Vercel compatible"
   git push origin main
   ```

2. **Deploy to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New Project"
   - Import your GitHub repository
   - Click "Deploy"

That's it! Vercel will automatically detect the `index.html` and deploy your site.

## 📁 Project Structure

```
├── index.html          # Main page
├── abegail.jpg         # Profile photo
├── bdo-qr.jpeg         # Bank QR code
├── gcash-qr.jpeg       # GCash QR code
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

## 🎨 Features

- Fully responsive design
- Neobrutalism aesthetic
- QR code payment integration (GCash & Bank)
- Transparent expense breakdown
- Fast loading with Tailwind CDN

## 🛠️ Local Development

Simply open `index.html` in your browser. No build process required!

## 📝 Customization

Edit `index.html` to update:
- Personal information
- Payment details
- Expense breakdown
- Profile photo

## 🔒 Security Headers

The `vercel.json` configuration includes security headers for:
- XSS Protection
- Clickjacking prevention
- Content type sniffing prevention
- Optimized caching for images

---

Made with 💛 for Abegail's Graduation
