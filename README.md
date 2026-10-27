# SWF Player

A static, browser-based Flash player powered by [Ruffle](https://ruffle.rs/). No server-side code is required. The player runs `.swf` files selected by the visitor or dropped onto the player area.

## Embed in Google Sites

1. Publish `index.html` on a static HTTPS host, such as GitHub Pages or Netlify. Keep the host's default framing permissions enabled.
2. In Google Sites, choose **Insert > Embed > By URL** and paste the published page URL.
3. Resize the embed to give the player enough room. A wide 16:9 area works well.

Google Sites embeds a webpage, so it cannot run this HTML directly as a standalone file. The published page loads the Ruffle runtime from jsDelivr; visitors need access to that CDN. Flash compatibility depends on Ruffle and may vary by SWF.