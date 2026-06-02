1. Project Overview

**Project Name:** SMART AI MEET
**Type:** Futuristic AI-Powered Education Platform (Web Application)
**Core Functionality:** Online classes, interviews, examinations, student verification, AI chatbot, smart monitoring
**Target Users:** Educational institutions, students, faculty members, administrators

---

## 2. UI/UX Specification

### 2.1 Layout Structure

**Global Layout:**
- Fixed premium navbar (80px height)
- Animated sidebar for dashboard (280px width, collapsible to 80px)
- Main content area with smooth page transitions
- Floating AI assistant widget (bottom-right)
- Custom elegant scrollbar

**Page Sections:**
- Landing: Hero → Features → Statistics → Testimonials → Footer
- Login: Centered card with split layout (form + 3D visuals)
- Dashboard: Sidebar + Main content with grid widgets
- Meeting Room: Video grid (70%) + Sidebar (30%)
- Test Page: Full-screen focused layout with timer bar
- Chatbot: Floating widget expandable to full panel

**Responsive Breakpoints:**
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

### 2.2 Visual Design

**Color Palette:**
```css
--bg-primary: #0a0a0f
--bg-secondary: #12121a
--bg-card: rgba(20, 20, 30, 0.7)
--bg-glass: rgba(255, 255, 255, 0.05)
--accent-blue: #00d4ff
--accent-purple: #8b5cf6
--accent-cyan: #22d3ee
--accent-pink: #f472b6
--text-primary: #ffffff
--text-secondary: #a1a1aa
--text-muted: #71717a
--border-glow: rgba(0, 212, 255, 0.3)
--gradient-start: #0a0a0f
--gradient-end: #1a1a2e
--success: #10b981
--warning: #f59e0b
--error: #ef4444
```

**Typography:**
- Headings: "Orbitron" (futuristic display font)
- Body: "Exo 2" (modern readable sans)
- Code/Stats: "JetBrains Mono" (monospace)
- H1: 56px / 700 weight
- H2: 40px / 600 weight
- H3: 28px / 600 weight
- Body: 16px / 400 weight
- Small: 14px / 400 weight

**Spacing System:**
- Base unit: 4px
- Section padding: 80px vertical
- Card padding: 24px
- Component gap: 16px
- Page margin: 32px

**Visual Effects:**
- Glassmorphism: backdrop-blur(20px), background rgba(255,255,255,0.05)
- Neumorphism: soft inner shadows with glow
- Cyberpunk: sharp neon borders, grid overlays
- Holographic: prismatic gradients, iridescent highlights
- Glow effects: box-shadow with accent colors, 20px blur

### 2.3 Components

**Navigation Bar:**
- Glassmorphic background with blur
- Logo (animated 3D icon + text)
- Nav links with hover glow
- Profile dropdown
- Notification bell with badge
- Theme toggle switch

**Cards:**
- Glassmorphic background
- Neon border on hover
- Scale transform (1.02) on hover
- Floating animation option
- Gradient overlay on images

**Buttons:**
- Primary: Gradient background (blue → purple), glow effect
- Secondary: Glass with border, glow on hover
- Icon: Circular, glass background
- States: hover (scale 1.05), active (scale 0.98), disabled (opacity 0.5)

**Forms:**
- Floating labels
- Glow border on focus
- Animated validation states
- Glassmorphic input fields

**3D Elements:**
- Floating geometric shapes
- Interactive 3D holographic display
- Animated particle systems
- Glass spheres with internal glow

---

## 3. Functionality Specification

### 3.1 Landing Page

**Hero Section:**
- Animated 3D AI hologram (rotating, glowing)
- Headline: "The Future of AI Education"
- Subheadline: "Transform your learning experience with intelligent AI-powered online education"
- Two CTA buttons: "Start Meeting" (primary), "Join Meeting" (secondary)
- Floating glass cards with features preview
- Animated particle background

**Statistics Section:**
- Animated counters (10,000+ Students, 500+ Courses, 50+ Institutions, 99.9% Uptime)
- Number counting animation on scroll
- Gradient progress bars

**Features Section:**
- 6 feature cards in grid (2x3)
- Icons with glow effects
- Hover animations
- Features: Online Classes, Online Interviews, Online Examinations, Student Verification, AI Chatbot, Smart Monitoring

**Testimonials:**
- Carousel with 3D card transforms
- Auto-play with pause on hover
- User avatars with glow rings

**Footer:**
- Multi-column layout
- Newsletter subscription
- Social links with hover animations
- Legal links

### 3.2 Login & Verification Page

**Login Form:**
- Email input with floating label
- Password input with show/hide toggle
- "Remember me" checkbox
- "Forgot password" link
- Submit button with loading state
- Social login options

**Verification Section:**
- Student ID upload zone (drag & drop)
- Camera frame for face verification
- AI scanning animation (circular sweep)
- Progress indicator (scanning → processing → complete)
- Success/error states

### 3.3 Dashboard

**Sidebar:**
- Collapsible with animation
- Navigation items: Dashboard, Classes, Tests, Interviews, Chatbot, Settings
- Active state with glow
- User profile mini card
- Logout button

**Stats Cards:**
- 4 cards: Total Students, Active Classes, Tests Completed, Interviews Scheduled
- Animated gradient backgrounds
- Icon with glow
- Trend indicator

**Quick Actions:**
- Start Instant Meeting button
- Schedule Class button
- Create Test button
- Verify Student button

**Sections:**
- Online Classes: Card grid with upcoming classes
- Online Tests: Active/past tests list
- Interviews: Scheduled upcoming interviews
- AI Assistant: Floating panel
- Activity Chart: Line graph of weekly activity
- Performance Widget: Radial progress charts

### 3.4 Meeting Room

**Video Grid:**
- 2x2 default layout (supports up to 4)
- Video tiles with name overlay
- Mute/camera off indicators
- Pin participant option
- Speaker highlight border

**Control Bar:**
- Floating glassmorphic bar at bottom
- Mic toggle (animated icon)
- Camera toggle
- Screen share button
- Chat toggle
- Participants toggle
- AI Assistant toggle
- End call button (red, prominent)

**Side Panels:**
- Chat: Message list, input, timestamps
- Participants: List with mute status
- AI Chatbot: Collapsible panel

**Features:**
- Connection quality indicator
- Recording indicator
- Timer display
- Floating minimize option

### 3.5 Online Test Page

**Header:**
- Test title
- Timer countdown (prominent)
- Progress bar
- Submit button

**Question Panel:**
- Question number and text
- Options as cards (A, B, C, D)
- Selected state with glow
- Navigation arrows

**Footer:**
- Question navigator (numbered dots)
- Flag question option
- Time remaining warning

**Security Features:**
- Full-screen warning popup
- Tab switch detection warning
- Copy/paste disabled
- Right-click disabled

### 3.6 AI Chatbot

**Floating Widget:**
- Circular button with pulse animation
- Expand to full panel on click

**Chat Panel:**
- AI avatar with glow
- Message bubbles (user right, AI left)
- Typing animation (3 dots bounce)
- Smart response suggestions
- Input with send button

**Features:**
- Conversation history
- Markdown support
- Code block rendering
- Quick action buttons

---

## 4. Animation Specifications

### 4.1 Global Animations

**Page Transitions:**
- Fade + slide (300ms ease-out)
- Staggered children (50ms delay)

**Hover Effects:**
- Scale: 1.02 (cards), 1.05 (buttons)
- Border glow: expand from center
- Background shift: gradient movement

**Scroll Animations:**
- Fade-in-up on viewport entry
- Parallax on backgrounds
- Staggered grid reveals

### 4.2 Special Animations

**3D Hologram:**
- Continuous rotation (Y-axis, 20s loop)
- Pulse glow (2s interval)
- Hover pause + zoom

**Particle Background:**
- 50 particles floating
- Mouse interaction (repel)
- Color: accent blue/purple

**Loading States:**
- Skeleton shimmer
- Spinner with glow
- Progress bar with pulse

**Success Animations:**
- Check mark draw
- Confetti burst
- Glow pulse

---

## 5. Acceptance Criteria

### Visual Checkpoints
- [ ] Dark theme with deep black background
- [ ] Neon accents (blue, purple, cyan) visible
- [ ] Glassmorphic cards render correctly
- [ ] Typography hierarchy clear and readable
- [ ] All animations smooth (60fps)
- [ ] Responsive at all breakpoints

### Functional Checkpoints
- [ ] Navigation between all pages works
- [ ] All buttons have hover/active states
- [ ] Forms show validation states
- [ ] Timer counts down in test page
- [ ] Chatbot sends and displays messages
- [ ] Video grid displays placeholder videos
- [ ] Sidebar collapses/expands

### Performance Checkpoints
- [ ] Initial load < 3 seconds
- [ ] Animations don't cause jank
- [ ] No console errors
- [ ] Assets load correctly

---

## 6. Technical Stack

- **Framework:** React 18 with Vite
- **Styling:** Tailwind CSS v3
- **Animation:** Framer Motion v11
- **3D:** React Three Fiber + Drei
- **Icons:** Lucide React
- **Routing:** React Router DOM v6
- **Charts:** Recharts
- **Fonts:** Google Fonts (Orbitron, Exo 2, JetBrains Mono)
