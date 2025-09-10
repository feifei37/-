# Game Site (English Version)

## Steps to Deploy

1. Upload these files to a **GitHub repository** (public or private).  
2. Go to **Cloudflare Pages** → Create a project → Connect your GitHub repo.  
   - Framework: None  
   - Build command: (leave empty)  
   - Output directory: `/`  
3. Deploy, then bind your domain in Cloudflare Pages → Custom domains.  
4. Edit `index.html`:  
   - Replace the game iframe `src` with a legal embed link.  
   - Update `example.com` with your real domain in `sitemap.xml` and `robots.txt`.  
   - Change `MyGameSite` and `support@example.com` to your own site name and email.  

Now your English site is live 🚀
