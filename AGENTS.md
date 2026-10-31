# Project architecture

This is a static single-page site. `index.html` contains all markup, styles, inline SVG artwork, and countdown behavior. `netlify.toml` publishes the root without a build command. No package installation is necessary.

Preserve the supplied Kabir Deewan branding, compact mobile layout, and Telegram destination. Keep the CTA href and JavaScript redirect URL synchronized. The manual CTA cancels the countdown to prevent a second navigation. Maintain keyboard focus visibility, browser zoom, reduced-motion support, and the no-JavaScript fallback.

Statistics and claims are static user-supplied copy; no live analytics or prediction service is implemented. There is no persistence or backend. Do not add a framework for routine content or style edits.
