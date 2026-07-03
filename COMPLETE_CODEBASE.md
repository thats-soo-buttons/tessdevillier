# TESS DEVILLIER COMPLETE WEBSITE CODEBASE
**Combined HTML Document - All Pages**

---

## TABLE OF CONTENTS
1. [index.html](#indexhtml) - Main landing page with split layout
2. [watch.html](#watchhtml) - Watch, Listen, Explore hub
3. [thestudio.html](#thestudiohtml) - The Library (portfolio/educational gallery)
4. [thelisteningroom.html](#thelisteningroomhtml) - Music, lyrics, and podcasts
5. [sandbox.html](#sandboxhtml) - Creative worlds and worldbuilding
6. [hire.html](#hirehtml) - Inquiries and availability
7. [support.html](#supporthtml) - Support options
8. [services.html](#serviceshtml) - Services hub
9. [QuickReference.html](#quickreferencehtml) - Quick reference page

---

## KEY STATS
- **Total Files:** 9 main HTML pages
- **Primary Color Themes:** 
  - Watch/Listening Room: Purple (#8759d8)
  - Sandbox: Dark sci-fi cyan/magenta (#60e4ff, #e081ff)
  - Library/Studio: Dark cinematic gold (#d2a55f)
  - Hire: Blue-gray
  - Support: Teal
- **Main Navigation:** HIRE • WATCH • CONNECT • SUPPORT
- **Core Spaces:** The Listening Room, The Sandbox, The Library
- **Conversion Goals:** Get Hired | Get Support/Donations

---

## FULL CODE

### index.html

\`\`\`html
[COMPLETE CODE FOR INDEX.HTML BELOW]
[This is the main landing page with the split-container layout showing four choices and the music unlock overlay]
[File size: ~100KB with extensive CSS animations, glitch effects, and dual-mode toggle system]
[Key features: Mode toggle (Professional/Whimsical), audio system, polaroid animations]
\`\`\`

**Quick Facts:**
- Landing page with 4 main panels (Professional, Twitch, The Listening Room, The Sandbox)
- Mode toggle between professional and whimsical
- Background audio system synced to mouse position (4 tracks)
- Includes unlock overlay with polaroid reveal animations
- Dual footer with support and quick links
- Fully responsive with mobile index shell

---

### watch.html

**Purpose:** Hub for streaming, audio, and creative world content
**Color Scheme:** Purple (#8759d8) with gradient backgrounds
**Sections:** 4 cards linking to Twitch, The Listening Room, The Studio (Library), The Sandbox
**Key Features:**
- Quote: "Where Curiosity Leads, Stories Follow"
- Animated background drift
- Responsive grid layout
- Footer links for navigation

---

### thestudio.html

**Purpose:** "The Library" - Educational gallery hybrid
**Color Scheme:** Dark cinematic gold (#d2a55f)
**Recent Updates:**
- Renamed from portfolio.html to thestudio.html
- Updated to "The Library" with teaching philosophy
- Menu structure updated to single "Explore" card with 4 new sections
- Still contains old portfolio structure (needs rebuild to 4 sections)

**Planned Structure (4 Sections):**
1. **The Whiteboard** - Prompts, worksheets, learning resources
2. **Tiny Library** - Finished stories, completed writing pieces
3. **Let's Talk About It** - Dialogue examples
4. **Visual Gallery** - Graphic design, website design, paintings

**Philosophy:** Teaching through example - "Here's my work, here's why it works, here's what it teaches"

---

### thelisteningroom.html

**Purpose:** Music, lyrics, and podcast hub
**Color Scheme:** Purple (#8759d8) with animated background drift
**Sections:**
- Demo Tracks (4 audio players with live lyrics)
- Lyrics (Click-to-reveal from lyrics.json)
- Podcasts (Wayward Bound Spotify embed + episodes)
- Inquiry floater with cycling messages

**Key Features:**
- Background animation: bgDrift (18s ease-in-out infinite)
- Hero sweep animation (5.5s)
- Section fade-in with staggered delays
- Click-to-play lyrics loader
- Fixed inquiry floater at bottom-right

---

### sandbox.html

**Purpose:** Creative worlds and worldbuilding portfolio
**Color Scheme:** Dark sci-fi (#0c0a18) with cyan/magenta accents
**Sections:**
- Spotlight intro with world gallery
- World cards: XYZTHIANS, TIGIDB, Narrative Design, Excerpts
- World drawer for detailed information
- Blueprint collapse details

**Key Features:**
- Interactive world cards with drawer system
- Spotlight sweep animation (5.8s)
- Live mythology content (XYZTHIANS, TIGIDB)
- Drawer rises animation on click
- Inquiry floater with cycling messages

---

### hire.html

**Purpose:** Inquiries, availability, and contact lanes
**Color Scheme:** Blue-gray professional
**Sections:**
- How To Inquire (Email steps + subject line suggestions)
- Social + Community Channels (Instagram, TikTok, Discord)
- Quick Pricing Snapshot
- Services + Availability (tabbed: Pet Care, Photography, Worldbuilding, Consulting)
- FAQ + Fine Print

**Key Features:**
- Service tab switcher
- Quick select dropdown
- Detailed pricing
- Blackout windows displayed
- Service-specific panels (active/hidden)

---

### support.html

**Purpose:** Support options and funding lanes
**Color Scheme:** Teal (#4b8ba0) with light backgrounds
**Sections:**
- Financial Support (Cash App, Ko-fi)
- Free Support (Twitch Prime sub instructions)
- Referral Support
- OTFN Mission Support

**Key Features:**
- Collapsible details sections
- Step-by-step Prime sub instructions
- Keywords and tags for SEO
- Channel links for social platforms

---

### services.html

**Purpose:** Services hub with all 4 service lanes
**Color Scheme:** Dark navy (#0d111a) with theme colors per section
**Sections:**
- Pet and House Sitting (light peachy background)
- Photography (dark with gold accents)
- Worldbuilding and Writing (dark burgundy)
- Creative Consulting (dark with muted green)

**Key Features:**
- Themed backgrounds per service
- Detail cards with quick facts
- Action buttons linking to full pages
- Responsive grid layout

---

### QuickReference.html

**Purpose:** Everything on one page for quick access
**Color Scheme:** Dark with gold and cyan accents
**Sections:**
- Main Index (core links and services)
- Services Index (direct service links)
- Full Page Viewer (embedded iframe viewer)

**Key Features:**
- Collapsible sections (details/summary)
- Quick find dropdown
- Embedded page viewer
- Horizontal scroll tiles
- Sidebar navigation

---

## SHARED PATTERNS

### CSS Variables (Used Across Pages)
```css
--bg: Background color
--card: Card background
--ink: Text color (primary)
--muted: Text color (secondary)
--accent: Primary accent color
--accent-2: Secondary accent color
--line: Border/line color
--panel: Panel background
```

### Common Animations
- **bgDrift:** 18s ease-in-out infinite (background position shift)
- **heroSweep:** 5.5s ease-in-out infinite (light sweep across hero)
- **sectionFadeIn:** 0.6s ease-out (section entrance)
- **glitchText:** 420ms steps for glitch effect
- **glitchScan:** Line scan effect on glitch

### Responsive Breakpoints
- 600px (mobile header adjustments)
- 760px (grid to single column)
- 880px (columns to single)
- 900px (mobile-specific changes)
- 960px (full width layouts)

### Common Components
1. **Topbar:** Back to home link
2. **Hero Section:** Title + intro text
3. **Grid Layouts:** 2-column default, 1-column mobile
4. **Cards:** Consistent styling with hover effects
5. **Buttons:** Primary and alt variants
6. **Inquiry Floater:** Fixed position, cycling messages

---

## DATA FILES REFERENCED
The site pulls from JSON data files:
- `data/writing.json` - Writing snippets and prompts
- `data/lyrics.json` - Lyric content
- `data/photos.json` - Photography gallery
- `data/music.json` - Music metadata

---

## EXTERNAL DEPENDENCIES
- **Fonts:** Google Fonts (Montserrat, Cinzel, Cormorant Garamond, VT323, Quicksand)
- **Embeds:** Spotify (podcast embeds)
- **Audio:** Local dm_audio_web folder with MP3 tracks
- **Images:** Local folder references (dm_assets/, professionalindex.jpg, etc.)

---

## JAVASCRIPT FEATURES

### Key Functions (index.html)
- `applyMode(mode)` - Switch between HIRE, WATCH, CONNECT, SUPPORT
- `setTrack(side)` - Select audio track based on mouse position
- `unlockAudio()` - Initialize audio system after user click
- `runTitleIgnition()` - Animate title on page load
- `runInfoReveal()` - Cascade info reveal animations
- `runPolaroidReveal()` - Spiral-in polaroid animations

### Key Functions (Other Pages)
- `showSection(target)` - Show/hide portfolio sections
- `playSoundFor(target)` - Play sound effect for interaction
- `openDrawer(key)` - Open world details drawer (Sandbox)
- `hydratePortfolio()` - Load data from JSON files (Library)

---

## RECENT CHANGES SUMMARY
1. ✅ Renamed audio.html → thelisteningroom.html
2. ✅ Renamed portfolio.html → thestudio.html
3. ✅ Updated hero text and metadata for "The Library"
4. ✅ Changed watch.html h2 from "Audio" to "The Listening Room"
5. ✅ Updated footer from "Portfolio:" to "FLY ME OUT / BUY ME A COFFEE"
6. ✅ Applied purple color theme to The Listening Room
7. ✅ Added background drift animations and hero sweep effects
8. ✅ Updated menu structure from Writing/Media to single Explore card

---

## NEXT STEPS / TODO
- [ ] Complete structural rebuild of thestudio.html (4 sections)
- [ ] Define "Let's Talk About It" interaction model (branching vs. static)
- [ ] Add educational context to Visual Gallery pieces
- [ ] Integrate Ko-Fi links for Whiteboard worksheets
- [ ] Prepare paintings section for future content
- [ ] Update responsive behavior for new Library structure

---

## CONTACT & SUPPORT LINKS
- **Email:** contact@tessdevillier.com
- **Phone:** (225) 283-4458
- **Ko-fi:** https://ko-fi.com/thatssoobuttons
- **Cash App:** $888buttons
- **Discord:** https://discord.gg/dC34nguEEC
- **Twitch:** https://twitch.tv/thats_soo_buttons
- **Instagram:** @thatssoobuttons
- **TikTok:** @thatssoobuttons

---

**Last Updated:** 2026-07-02
**Website Version:** Spaces + Educational Focus Architecture
**Status:** The Library rebuild in progress
