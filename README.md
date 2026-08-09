# TrendScope — Deploy Guide (Simple Steps)

## Step 1: GitHub par account banao
1. github.com pe jao, free account banao
2. "New repository" pe click karo, naam do "trendscope", Create karo

## Step 2: Ye files GitHub pe upload karo
1. Apne naye repository page pe "uploading an existing file" link pe click karo
2. Is poore folder ke andar ki SAARI files aur folders (package.json, index.html, src/, api/, vite.config.js) upload karo
3. "Commit changes" dabao

## Step 3: Vercel se deploy karo
1. vercel.com pe jao, "Sign up" → "Continue with GitHub" se login karo
2. "Add New Project" dabao
3. Apna "trendscope" repository select karo → "Import"
4. Deploy se pehle "Environment Variables" section me:
   - Name: `ANTHROPIC_API_KEY`
   - Value: apni API key (console.anthropic.com se milegi — "Get API Key" section me account banake)
5. "Deploy" dabao — 1-2 minute me live link mil jayega (jaise `trendscope.vercel.app`)

## Step 4: Test karo
Apna live link kholo, ek chart screenshot upload karke "Analyze" try karo.

## Zaroori baatein
- Har chart analysis ka Anthropic API thoda sa charge karta hai (paise ka bill account me banta hai) — pricing console.anthropic.com pe dekh sakte ho
- Real subscription payment (₹599) ke liye Razorpay integrate karna hoga — ye is project me abhi nahi hai
- Custom domain (jaise trendscope.in) Vercel ke "Domains" setting me add kar sakte ho, GoDaddy/Namecheap se khareed ke
