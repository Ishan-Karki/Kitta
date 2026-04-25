---
name: Kitta
colors:
  surface: '#0d1515'
  surface-dim: '#0d1515'
  surface-bright: '#333b3b'
  surface-container-lowest: '#080f10'
  surface-container-low: '#151d1e'
  surface-container: '#192122'
  surface-container-high: '#232b2c'
  surface-container-highest: '#2e3637'
  on-surface: '#dce4e5'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#dce4e5'
  inverse-on-surface: '#2a3233'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#c1c6d7'
  on-secondary: '#2a303d'
  secondary-container: '#434957'
  on-secondary-container: '#b3b8c8'
  tertiary: '#fff5de'
  on-tertiary: '#3b2f00'
  tertiary-container: '#fed639'
  on-tertiary-container: '#715d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#dde2f3'
  secondary-fixed-dim: '#c1c6d7'
  on-secondary-fixed: '#161c27'
  on-secondary-fixed-variant: '#414754'
  tertiary-fixed: '#ffe179'
  tertiary-fixed-dim: '#eac324'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#554500'
  background: '#0d1515'
  on-background: '#dce4e5'
  surface-variant: '#2e3637'
typography:
  h1:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  data-mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin: 32px
  panel-padding: 24px
  stack-xs: 4px
  stack-sm: 12px
  stack-md: 20px
  stack-lg: 40px
---

## Brand & Style
The brand personality centers on the intersection of high-finance stability and cutting-edge artificial intelligence. It conveys a sense of "calm intelligence"—where complex NEPSE market data is distilled into actionable, premium insights without overwhelming the user. 

The design style utilizes **Sleek Modernism** with **Subtle Glassmorphism**. This approach balances the heavy, institutional feel of traditional finance with the translucent, airy qualities of modern AI interfaces. The aesthetic is high-fidelity and professional, favoring precision and clarity over decorative elements. It aims to evoke a sense of being "inside the machine," providing users with a sophisticated vantage point over the market.

## Colors
The color palette of this design system is anchored in deep, dark tones to reduce eye strain during prolonged analysis. The **Midnight Blue** background provides a foundational depth, while **Slate Panels** are used to define information architecture and grouping.

The **Electric Cyan** primary accent is reserved for AI-driven highlights, active states, and focus areas, signaling the "intelligence" layer of the platform. For market signals, a high-vibrancy semantic set is used: **Vibrant Green** for bullish momentum (Buy), **Bright Red** for bearish signals (Sell), and **Amber** for neutral stability (Hold). Text follows a hierarchy of off-whites and cool greys to maintain high legibility against the dark canvases without creating harsh contrast.

## Typography
This design system utilizes **Manrope** for its balance of geometric modernism and high-readability functionalism. It feels technical yet refined, making it ideal for financial data. 

Headlines use tighter tracking and heavier weights to command authority. Body text is optimized for long-form market reports with generous line heights. A specific "Data Mono" style (using Inter) is designated for numerical values and ticker symbols to ensure tabular alignment and clarity in dense data visualizations. All labels for charts and minor UI elements utilize a bold, uppercase style to differentiate meta-information from primary content.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy within a 1440px max-width container to ensure that complex dashboards remain predictable and balanced across desktop monitors. A 12-column system is used with 24px gutters to provide significant breathing room between data modules.

The spacing rhythm is based on an **8px base unit**, ensuring mathematical harmony across all components. Vertical stacks favor generous white space (or "dark space") to prevent the data-heavy environment from feeling cluttered. Content density is managed through tiered padding: high-level dashboard overviews use larger margins (stack-lg), while granular data tables use tighter internal spacing (stack-xs).

## Elevation & Depth
In this design system, depth is achieved through **Tonal Layering** and **Subtle Glassmorphism**. 

1. **Surface 0 (Midnight Blue):** The application canvas.
2. **Surface 1 (Slate Panels):** The primary container level for widgets and charts. These use a subtle 1px inner stroke (border-top/left) to simulate a light source.
3. **Surface 2 (Glass Overlays):** Modal windows and dropdown menus utilize a backdrop blur (20px-30px) with 60% opacity Slate backgrounds. This creates a "premium lens" effect.
4. **Interactive Glows:** AI-driven insights use a low-opacity Electric Cyan outer glow (blur: 15px, spread: 2px) to signify importance without using traditional heavy shadows. 

Shadows, when used, are ambient and tinted with the background hue (#080A0F) to remain unobtrusive and integrated.

## Shapes
The shape language is defined as **Rounded (Level 2)**. This choice softens the "cold" nature of financial data, making the platform feel more accessible and human-centric. 

Standard components like buttons and input fields feature an 8px (0.5rem) radius. Larger layout containers and dashboard cards utilize a 16px (1rem) radius to create a distinct framing effect. For status indicators—such as "Buy" or "Sell" tags—a fully pill-shaped (rounded-full) geometry is used to distinguish these interactive or status-based chips from structural layout elements.

## Components
- **Buttons:** Primary buttons use a solid Electric Cyan fill with dark text. Secondary buttons are "Ghost" style with Cyan borders. AI-specific actions feature a subtle gradient border.
- **Cards/Panels:** Defined by the Slate color, they feature a 1px border (#2D3748) to separate them from the background. Headers within cards should have a subtle bottom-border.
- **Chips & Badges:** Small, pill-shaped markers. "Buy" badges use a soft green glow; "Sell" badges use a soft red glow. Text inside should be bold and high-contrast.
- **Input Fields:** Darker than the panel color with a 1px Slate border. On focus, the border transitions to Electric Cyan with a micro-glow.
- **Data Visualization:** Charts should use minimal grid lines (Low-contrast grey). The "Electric Cyan" line represents AI predictions, while "Off-white" represents historical data.
- **AI Insight Module:** A special card component with a 2px Electric Cyan left-accent border and a very subtle glassmorphism background to highlight its "intelligent" nature.