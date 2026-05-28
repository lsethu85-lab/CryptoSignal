# Crypto Momentum Dashboard

A self-contained crypto analytics dashboard built as a single HTML application for scanning market momentum, tracking portfolio ideas, and managing virtual holdings with local save/export/import support.

## Author
**Sethuraman Lakshminarayanan**

## Highlights

- **Scanner** for crypto momentum discovery
- **My Portfolio** for tracked assets and analysis cards
- **My Virtual Holdings** for simulated positions
- **Save Local** for browser persistence
- **Export JSON / Import JSON** for portability across browsers or devices
- **Dark / Light theme** support
- **Responsive UI** optimized for desktop and mobile

## Tabs Included

1. **Scanner**
   - Market scanning
   - Filters, heatmap, laggard watch, radar logic

2. **My Portfolio**
   - Tracked crypto ideas
   - Analysis cards
   - Portfolio insights

3. **My Virtual Holdings**
   - Number of shares
   - Average buy price
   - Current market price
   - Total investment
   - Current value
   - Unrealized P/L and P/L %
   - Search, sort, edit, remove
   - Allocation visualization
   - Save / Export / Import

4. **Quick Picks**
5. **Alpha Feed v2**
6. **Logic**

## Cross-Device Workflow

Because **localStorage** is browser-specific, use the JSON portability flow when moving to another browser or machine:

1. Open **My Virtual Holdings**
2. Click **Export JSON**
3. Copy the downloaded file to another device
4. Open the dashboard there
5. Click **Import JSON**

## Files in This Package

- `index.html` — full latest dashboard with branding
- `README.md` — project documentation

## Run Locally

You can open `index.html` directly in a browser. For the best experience, use a modern Chromium-based browser or Firefox.

## Branding

The dashboard title includes a small subtitle:

> Powered by Sethu

## Notes

- Market and analytics features rely on public API availability.
- Some advanced modules may behave differently if third-party endpoints are rate-limited.
- Local save is browser-specific; export/import is the portable option.

## Credits

Built and maintained by **Sethuraman Lakshminarayanan**.
