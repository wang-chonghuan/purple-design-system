# Financial Analytics Web App Design System

## 1. Brand Colors

### Core Brand Colors
- Primary Purple: `#8163DD`
  - Used for: Primary CTAs, active states, brand elements
  - Gradient: Can be used in combination with Tertiary Blue
- Secondary Blue: `#679FF0`
  - Used for: Secondary actions, supporting elements, data visualization
- Tertiary Blue: `#3F64F2`
  - Used for: Accent elements, gradient endpoints

### Neutral Colors
- Background: `#F8FAFD` (Light blue-tinted background)
- Surface: `#FFFFFF` (Pure white for cards and elevated elements)
- Border: `#E6E8F0` (Subtle borders and dividers)
- Overlay: `rgba(0,0,0,0.05)` (For shadows and overlays)

### Text Colors
- Primary Text: `#1A1F36` (Deep blue-black)
- Secondary Text: `#4E5D78` (Muted blue-grey)
- Disabled Text: `#A6B1C2`

### Semantic Colors
- Success: `#34A853`
  - Background: `#E6F4EA`
- Warning: `#FBBC04`
  - Background: `#FEF7E0`
- Error: `#EA4335`
  - Background: `#FCE8E6`
- Info: Background same as Secondary Blue with 10% opacity

### Gradients
- Primary Gradient: `linear-gradient(135deg, #8163DD, #3F64F2)`
  - Used for: Key CTAs, headers, important UI elements

## 2. Typography

### Font Family
- Primary: Inter
- Fallback: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif

### Font Sizes
- Display: 32px (2rem)
- H1: 24px (1.5rem)
- H2: 18px (1.125rem)
- H3: 16px (1rem)
- Body: 14px (0.875rem)
- Small: 12px (0.75rem)
- Micro: 10px (0.625rem)

### Font Weights
- Regular: 400
- Medium: 500
- Semi-bold: 600
- Bold: 700

### Line Heights
- Tight (Headings): 1.3
- Normal (Body): 1.5
- Relaxed (Large text): 1.7

## 3. Spacing System

### Base Unit
- 4px grid system

### Spacing Scale
- xs: 4px (0.25rem)
- sm: 8px (0.5rem)
- md: 12px (0.75rem)
- lg: 16px (1rem)
- xl: 24px (1.5rem)
- 2xl: 32px (2rem)

### Component Spacing
- Card padding: 12px
- Section padding: 16px
- List item padding: 8px
- Form field spacing: 12px
- Button padding: 0 12px (horizontal)

## 4. Layout

### Container Widths
- Mobile: 100% - 24px
- Tablet: 768px
- Desktop: 1200px

### Breakpoints
- Mobile: 320px - 767px
- Tablet: 768px - 1023px
- Desktop: 1024px+

### Grid System
- 4-column grid on mobile (gap: 12px)
- 8-column grid on tablet (gap: 16px)
- 12-column grid on desktop (gap: 16px)

## 5. Shadows & Elevation

### Shadow Scale
- xs: `0 1px 2px rgba(0,0,0,0.05)`
- sm: `0 1px 3px rgba(0,0,0,0.1)`
- md: `0 2px 4px rgba(0,0,0,0.1)`
- lg: `0 4px 6px rgba(0,0,0,0.1)`

## 6. Border Radius

### Radius Scale
- sm: 6px
- md: 8px
- lg: 12px
- xl: 16px
- full: 9999px (For pills and circular elements)

## 7. UI Components

### Buttons
- Height: 36px
- Padding: 0 12px
- Border radius: 6px
- Font: 14px, Weight: 500
- States:
  - Default: Primary gradient or solid color
  - Hover: 90% opacity + translateY(-1px)
  - Active: 95% opacity + translateY(0)
  - Disabled: 40% opacity

### Input Fields
- Height: 36px
- Padding: 0 12px
- Border: 1px solid border color
- Border radius: 6px
- States:
  - Focus: Primary color border + rgba(primary, 0.1) shadow
  - Error: Error color border
  - Disabled: Background opacity 50%

### Cards
- Background: White
- Border: 1px solid border color
- Border radius: 8px
- Padding: 12px
- Shadow: sm
- Hover: Transform translateY(-2px) + md shadow

### Tables
- Header:
  - Background: Background color
  - Font: 13px, Weight: 500
  - Text color: Secondary text
- Cells:
  - Padding: 8px 12px
  - Border: 1px solid border color
  - Font size: 14px
- Alternate rows: Background color
- Hover: Subtle highlight

## 8. Navigation

### Bottom Navigation
- Height: 48px + safe area
- Background: Surface color with blur backdrop
- Active state:
  - Color: Primary
  - Background: rgba(primary, 0.1)
- Item spacing: 8px
- Font size: 12px

## 9. Motion

### Transitions
- Default: 150ms ease-in-out
- Complex animations: 200ms ease-in-out
- Page transitions: 300ms ease-in-out

### Hover States
- Scale: transform: scale(1.02)
- Lift: transform: translateY(-2px)
- Fade: opacity: 0.9

## 10. Data Visualization

### Chart Colors
Primary palette for sequential data:
1. `#8163DD` (Primary)
2. `#679FF0` (Secondary)
3. `#3F64F2` (Tertiary)
4. `#A78BF5` (Light Purple)
5. `#8DB5F4` (Light Blue)

### Graph Elements
- Grid lines: Border color
- Axes: Secondary text color
- Labels: 12px, Secondary text color
- Tooltips: Dark surface with 8px radius

## 11. Best Practices

### Mobile First
- Design for smallest screens first
- Progressive enhancement for larger screens
- Touch targets minimum 44x44px
- Bottom-aligned primary actions

### Visual Hierarchy
- Use size, weight, and color for importance
- Maintain consistent spacing rhythm
- Group related information
- Use whitespace to improve readability

### Accessibility
- Color contrast ratio: 4.5:1 minimum
- Focus states must be visible
- Touch targets properly spaced
- Text remains legible at 200% zoom

### Performance
- Use SVG for icons
- Optimize images and animations
- Minimize shadow usage on mobile
- Reduce unnecessary visual complexity