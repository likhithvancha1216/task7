# Report — Chrome Extensions Audit

## Initial State  
Chrome browser had multiple extensions installed, including VPN tools, download helpers, and search modifiers.

## Methodology  
1. Opened `chrome://extensions/`  
2. For each extension, reviewed details such as permissions, Web Store listing, developer, reviews, and last update date  
3. Disabled suspicious extensions temporarily and monitored browsing behavior  
4. Removed confirmed malicious or unnecessary extensions  
5. Cleared cache, reset default search engine, restarted browser  

## Removed / Disabled Extensions  
- Hola Free VPN Proxy  
- SaveFrom.net Helper  
- Search Manager  
- Fake "Super Ad Blocker"  

(See `removed-list.md` for full table.)  

## Findings & Observations  
- Hola VPN had excessive permissions and a history of unsafe practices  
- SaveFrom.net Helper attempted to hijack downloads and was blocked by Chrome policies  
- Search Manager forced search engine changes and homepage redirects  
- A fake ad blocker actually injected its own ads  

## Recommendations & Best Practices  
- Only install extensions from reputable developers with strong reviews  
- Regularly audit extensions and review new permissions after updates  
- Disable Chrome extension sync if malicious ones keep reappearing  
- Avoid third-party “helper” extensions for downloads or media — they often violate policies  

## Conclusion  
4 suspicious extensions were removed. Chrome browser was restored to a safe state with only essential, verified extensions.

