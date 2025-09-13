# VoYatra Travel Website Design Guidelines

## Design Approach
**Reference-Based Approach** - Drawing inspiration from Airbnb and Booking.com for their travel-focused, experience-driven design patterns while maintaining originality for VoYatra's unique feature set.

## Core Design Elements

### A. Color Palette
**Primary Colors:**
- Brand Primary: 220 85% 45% (Deep travel blue)
- Secondary: 195 75% 35% (Ocean teal)

**Light Mode:**
- Background: 0 0% 98%
- Surface: 0 0% 100%
- Text Primary: 220 15% 20%
- Text Secondary: 220 10% 45%

**Dark Mode:**
- Background: 220 15% 8%
- Surface: 220 12% 12%
- Text Primary: 0 0% 95%
- Text Secondary: 220 5% 70%

**Accent Colors:**
- Success (budget on track): 145 70% 45%
- Warning (budget alert): 35 85% 55%
- Emergency: 0 75% 55%

### B. Typography
- **Primary Font:** Inter (Google Fonts) - Clean, modern readability
- **Display Font:** Poppins (Google Fonts) - For headings and brand elements
- **Sizes:** text-sm, text-base, text-lg, text-xl, text-2xl, text-3xl

### C. Layout System
**Spacing Units:** Tailwind units of 2, 4, 6, 8, 12, 16
- Micro spacing: p-2, m-2
- Component spacing: p-4, gap-4
- Section spacing: p-8, my-12
- Page margins: px-6, max-width containers

### D. Component Library

**Navigation:**
- Sticky header with VoYatra logo
- Main navigation: Dashboard, Budget, Map, Weather, Reviews, Chat, Profile
- Mobile: Collapsible hamburger menu

**Core Components:**
- **Budget Cards:** Clean expense tracking with progress bars
- **Map Container:** Full-width interactive map with overlay controls
- **Weather Widget:** Compact current conditions with forecast
- **Review Cards:** Photo-first layout with rating stars
- **Chat Interface:** WhatsApp-inspired messaging UI
- **News Feed:** Card-based layout with emergency indicators
- **Profile Timeline:** Instagram-inspired journey showcase

**Forms:**
- Rounded input fields (rounded-lg)
- Primary buttons with travel blue
- Outline buttons with blurred backgrounds on images

**Data Displays:**
- Budget progress rings and bars
- Location pins and markers
- Weather icons and charts
- Review star ratings
- Emergency status badges

## Visual Treatment

### Hero Section
Large hero image featuring diverse travelers with mountain/beach landscape. Overlay with VoYatra branding and primary CTA "Plan Your Next Adventure."

### Background Treatments
- Subtle gradient overlays on hero (220 85% 45% to 195 75% 35%)
- Clean white/dark surfaces for content areas
- Soft shadows and subtle borders for card elevation

### Images
**Hero Image:** Full-width travel landscape with diverse group of travelers
**Feature Cards:** Destination photos, food imagery, cultural landmarks
**Profile Sections:** User travel photos, journey milestones
**Weather Widgets:** Location-specific imagery
**Emergency Alerts:** Clear iconography for safety information

### Interaction Patterns
- Smooth transitions between budget views
- Real-time map updates with animated markers
- Live chat with typing indicators
- Instant photo upload with preview
- Emergency alerts with prominent red styling

## Key Design Principles
1. **Travel-First:** Every design decision prioritizes the travel experience
2. **Safety Priority:** Emergency features are prominently accessible
3. **Social Connection:** Group features encourage collaboration
4. **Financial Clarity:** Budget tracking is intuitive and stress-free
5. **Mobile Excellence:** Touch-friendly design for on-the-go usage