root.css
Note: root.css does not provide utility classes.
It defines design tokens (custom properties) used by other modules. Below is a quick reference for each token’s primary purpose or value.

Color Tokens
--color-primary-50: #eff6ff

--color-primary-100: #dbeafe

--color-primary-200: #bfdbfe

--color-primary-300: #93c5fd

--color-primary-400: #60a5fa

--color-primary-500: #3b82f6

--color-primary-600: #2563eb

--color-primary-700: #1d4ed8

--color-primary-800: #1e40af

--color-primary-900: #1e3a8a

--color-secondary-50: #fdf2f8

--color-secondary-100: #fce7f3

--color-secondary-200: #fbcfe8

--color-secondary-300: #f9a8d4

--color-secondary-400: #f472b6

--color-secondary-500: #ec4899

--color-secondary-600: #db2777

--color-secondary-700: #be185d

--color-secondary-800: #9d174d

--color-secondary-900: #831843

--color-accent-50: #f0fdf4

--color-accent-100: #dcfce7

--color-accent-200: #bbf7d0

--color-accent-300: #86efac

--color-accent-400: #4ade80

--color-accent-500: #22c55e

--color-accent-600: #16a34a

--color-accent-700: #15803d

--color-accent-800: #166534

--color-accent-900: #14532d

--color-gray-50: #f9fafb

--color-gray-100: #f3f4f6

--color-gray-200: #e5e7eb

--color-gray-300: #d1d5db

--color-gray-400: #9ca3af

--color-gray-500: #6b7280

--color-gray-600: #4b5563

--color-gray-700: #374151

--color-gray-800: #1f2937

--color-gray-900: #111827

--color-success-500: #10b981

--color-warning-500: #f59e0b

--color-error-500: #ef4444

Typography Tokens
--font-sans: system-ui, ...

--font-serif: Georgia, ...

--font-mono: Menlo, Monaco, ...

--font-size-xs: 0.75rem

--font-size-sm: 0.875rem

--font-size-base: 1rem

--font-size-lg: 1.125rem

--font-size-xl: 1.25rem

--font-size-2xl: 1.5rem

--font-size-3xl: 1.875rem

--font-size-4xl: 2.25rem

--font-size-5xl: 3rem

--font-size-6xl: 3.75rem

--font-weight-light: 300

--font-weight-normal: 400

--font-weight-medium: 500

--font-weight-semibold: 600

--font-weight-bold: 700

--line-height-tight: 1.1

--line-height-normal: 1.5

--line-height-relaxed: 1.75

--letter-spacing-tight: -0.05em

--letter-spacing-normal: 0

--letter-spacing-wide: 0.05em

Spacing Tokens
--space-0: 0
--space-1: 0.25rem
--space-2: 0.5rem
--space-3: 1rem
--space-4: 1.5rem
--space-5: 2rem
--space-6: 2.5rem
--space-7: 3rem
--space-8: 4rem
--space-9: 5rem
--space-10: 6rem
Borders & Radius
--radius-none: 0

--radius-sm: 0.125rem

--radius-md: 0.375rem

--radius-lg: 0.5rem

--radius-full: 9999px

--border-width-thin: 1px

--border-width-normal: 2px

--border-width-thick: 4px

Shadows
--shadow-xs: 0 1px 2px rgba(0, 0, 0, 0.05)
--shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.1)
--shadow-md: 0 4px 6px rgba(0, 0, 0, 0.1)
--shadow-lg: 0 10px 15px rgba(0, 0, 0, 0.15)
--shadow-xl: 0 20px 25px rgba(0, 0, 0, 0.2)
--shadow-2xl: 0 25px 50px rgba(0, 0, 0, 0.25)
--shadow-inner: inset 0 2px 4px rgba(0, 0, 0, 0.06)
--shadow-none: none
Z-Index
--z-index-dropdown: 1000
--z-index-sticky: 1020
--z-index-fixed: 1030
--z-index-modal-backdrop: 1040
--z-index-modal: 1050
--z-index-popover: 1060
--z-index-tooltip: 1070
Transitions
--transition-fast: all 0.2s ease-in-out
--transition-base: all 0.3s ease
--transition-slow: all 0.5s ease
Breakpoints
--breakpoint-xs: 0
--breakpoint-sm: 640px
--breakpoint-md: 768px
--breakpoint-lg: 1024px
--breakpoint-xl: 1280px
--breakpoint-2xl: 1536px
Container Widths
--container-sm: 100%
--container-md: 640px
--container-lg: 768px
--container-xl: 1024px
--container-2xl: 1280px

Container
.container – Centers content, sets responsive max-width based on --container-* tokens.
Display Utilities
.d-none – display: none
.d-block – display: block
.d-inline – display: inline
.d-inline-block – display: inline-block
.d-flex – display: flex
.d-inline-flex – display: inline-flex
.d-grid – display: grid
.d-inline-grid – display: inline-grid
Flex Direction & Wrapping
(Note: Some additional flex utilities appear in flex-grid.css. Below are the basics.)

.flex-row – flex-direction: row
.flex-row-reverse – flex-direction: row-reverse
.flex-column – flex-direction: column
.flex-column-reverse – flex-direction: column-reverse
.flex-wrap – flex-wrap: wrap
.flex-nowrap – flex-wrap: nowrap
Flex Alignment
.items-start – align-items: flex-start
.items-center – align-items: center
.items-end – align-items: flex-end
.justify-start – justify-content: flex-start
.justify-center – justify-content: center
.justify-end – justify-content: flex-end
.justify-between – justify-content: space-between
.justify-around – justify-content: space-around
.justify-evenly – justify-content: space-evenly
Positioning
.pos-static – position: static
.pos-relative – position: relative
.pos-absolute – position: absolute
.pos-fixed – position: fixed
.pos-sticky – position: sticky
Overflow
.overflow-auto – overflow: auto
.overflow-hidden – overflow: hidden
.overflow-scroll – overflow: scroll
.overflow-visible – overflow: visible
.overflow-x-auto – overflow-x: auto
.overflow-y-auto – overflow-y: auto
.overflow-x-hidden – overflow-x: hidden
.overflow-y-hidden – overflow-y: hidden
.overflow-x-scroll – overflow-x: scroll
.overflow-y-scroll – overflow-y: scroll
Responsive Variants
All classes above can be used with sm:, md:, and lg: prefixes to apply them from that breakpoint upward. For example:

.sm:d-none – display: none at min-width: var(--breakpoint-sm)
.md:pos-absolute – position: absolute at min-width: var(--breakpoint-md)
.lg:overflow-x-scroll – overflow-x: scroll at min-width: var(--breakpoint-lg)
(No additional unexpanded utilities are present here; for example, mt- or mb- classes appear in spacing.css, not here.)

spacing.css
Margin
.m-0 – margin: var(--space-0)
.m-1 – margin: var(--space-1)
.m-2 – margin: var(--space-2)
.m-3 – margin: var(--space-3)
.m-4 – margin: var(--space-4)
.m-5 – margin: var(--space-5)
.m-6 – margin: var(--space-6)
Top/Right/Bottom/Left

.mt-* – margin-top
.mr-* – margin-right
.mb-* – margin-bottom
.ml-* – margin-left
X/Y Axis

.mx-* – margin-left and margin-right
.my-* – margin-top and margin-bottom
Negative Margin
. -m-1 – margin: -var(--space-1)
. -m-2 – margin: -var(--space-2)
. -m-3 – margin: -var(--space-3)
. -m-4 – margin: -var(--space-4)
. -m-5 – margin: -var(--space-5)
. -m-6 – margin: -var(--space-6)
You can add more negative margin classes similarly (e.g., -m-7) if needed.

Margin Auto
.m-auto – margin: auto
.mt-auto – margin-top: auto
.mr-auto – margin-right: auto
.mb-auto – margin-bottom: auto
.ml-auto – margin-left: auto
.mx-auto – margin-left & margin-right: auto
.my-auto – margin-top & margin-bottom: auto
Padding
.p-0 – padding: var(--space-0)
.p-1 – padding: var(--space-1)
.p-2 – padding: var(--space-2)
.p-3 – padding: var(--space-3)
.p-4 – padding: var(--space-4)
.p-5 – padding: var(--space-5)
.p-6 – padding: var(--space-6)
Top/Right/Bottom/Left

.pt-* – padding-top
.pr-* – padding-right
.pb-* – padding-bottom
.pl-* – padding-left
X/Y Axis

.px-* – padding-left & padding-right
.py-* – padding-top & padding-bottom
Responsive Variants
All margin and padding classes can be prefixed with sm:, md:, or lg: (or more breakpoints if extended) to apply them at different viewport sizes.

.sm:m-1 – margin: var(--space-1) at min-width: var(--breakpoint-sm)
.md:p-4 – padding: var(--space-4) at min-width: var(--breakpoint-md)
.lg:mx-auto – margin-left & margin-right: auto at min-width: var(--breakpoint-lg)
sizing.css
Width
.w-auto – width: auto
.w-full – width: 100%
.w-min – width: min-content
.w-max – width: max-content
.w-fit – width: fit-content
Fixed Widths from Spacing

.w-0 – width: var(--space-0)
.w-1 – width: var(--space-1)
.w-2 – width: var(--space-2)
.w-3 – width: var(--space-3)
.w-4 – width: var(--space-4)
.w-5 – width: var(--space-5)
.w-6 – width: var(--space-6)
Fractional Widths

.w-1/2 – width: 50%
.w-1/3 – width: 33.3333%
.w-2/3 – width: 66.6667%
.w-1/4 – width: 25%
.w-2/4 – width: 50% (same as .w-1/2)
.w-3/4 – width: 75%
Screen & Max-Width

.w-screen – width: 100vw

.max-w-none – max-width: none

.max-w-full – max-width: 100%

.max-w-sm – max-width: var(--container-sm)

.max-w-md – max-width: var(--container-md)

.max-w-lg – max-width: var(--container-lg)

.max-w-xl – max-width: var(--container-xl)

.max-w-2xl – max-width: var(--container-2xl)

Min-Width

.min-w-0 – min-width: 0
.min-w-full – min-width: 100%
.min-w-min – min-width: min-content
.min-w-max – min-width: max-content
Height
.h-auto – height: auto
.h-full – height: 100%
.h-0 – height: var(--space-0)
.h-1 – height: var(--space-1)
.h-2 – height: var(--space-2)
.h-3 – height: var(--space-3)
.h-4 – height: var(--space-4)
.h-5 – height: var(--space-5)
.h-6 – height: var(--space-6)
Screen & Max-Height

.h-screen – height: 100vh
.max-h-full – max-height: 100%
.max-h-screen – max-height: 100vh
Min-Height

.min-h-0 – min-height: 0
.min-h-full – min-height: 100%
.min-h-screen – min-height: 100vh
Responsive Variants
All sizing classes can be prefixed with sm:, md:, or lg: to apply them from that breakpoint upward. Examples:

.sm:w-1/2 – width: 50% at min-width: var(--breakpoint-sm)
.md:h-screen – height: 100vh at min-width: var(--breakpoint-md)
.lg:max-w-xl – max-width: var(--container-xl) at min-width: var(--breakpoint-lg)
Note:

You can extend these patterns for additional spacing/sizing increments or breakpoints (e.g., xl: or 2xl:).
Negative margins can also be created for more spacing values (-m-7, -m-8, etc.).
Fractional widths or heights can be expanded similarly if you need more w-5/6, w-7/12, etc.

typography.css
Font Family
.font-sans – font-family: var(--font-sans), sans-serif
.font-serif – font-family: var(--font-serif), serif
.font-mono – font-family: var(--font-mono), monospace
Font Size
.text-xs – font-size: var(--font-size-xs)
.text-sm – font-size: var(--font-size-sm)
.text-base – font-size: var(--font-size-base)
.text-lg – font-size: var(--font-size-lg)
.text-xl – font-size: var(--font-size-xl)
.text-2xl – font-size: var(--font-size-2xl)
.text-3xl – font-size: var(--font-size-3xl)
.text-4xl – font-size: var(--font-size-4xl)
.text-5xl – font-size: var(--font-size-5xl)
.text-6xl – font-size: var(--font-size-6xl)
Font Weight
.font-light – font-weight: var(--font-weight-light)
.font-normal – font-weight: var(--font-weight-normal)
.font-medium – font-weight: var(--font-weight-medium)
.font-semibold – font-weight: var(--font-weight-semibold)
.font-bold – font-weight: var(--font-weight-bold)
Line Height
.leading-tight – line-height: var(--line-height-tight)
.leading-normal – line-height: var(--line-height-normal)
.leading-relaxed – line-height: var(--line-height-relaxed)
Letter Spacing
.tracking-tight – letter-spacing: var(--letter-spacing-tight)
.tracking-normal – letter-spacing: var(--letter-spacing-normal)
.tracking-wide – letter-spacing: var(--letter-spacing-wide)
Text Alignment
.text-left – text-align: left
.text-center – text-align: center
.text-right – text-align: right
.text-justify – text-align: justify
Text Decoration
.underline – text-decoration: underline
.line-through – text-decoration: line-through
.no-underline – text-decoration: none
Text Transform
.uppercase – text-transform: uppercase
.lowercase – text-transform: lowercase
.capitalize – text-transform: capitalize
.normal-case – text-transform: none
Responsive Variants
.sm:text-sm – sets font-size: var(--font-size-sm) at min-width: var(--breakpoint-sm)
.md:text-right – sets text-align: right at min-width: var(--breakpoint-md)
.lg:font-bold – sets font-weight: var(--font-weight-bold) at min-width: var(--breakpoint-lg)
(Repeat for other classes as desired.)

background.css
Background Colors
Primary Scale

.bg-primary-50 – background-color: var(--color-primary-50)
(Similarly .bg-primary-100, .bg-primary-200, up to .bg-primary-900)
Secondary Scale

.bg-secondary-50 – background-color: var(--color-secondary-50)
(Similarly .bg-secondary-100, .bg-secondary-200, up to .bg-secondary-900)
Accent Scale

.bg-accent-50 – background-color: var(--color-accent-50)
(Similarly .bg-accent-100 up to .bg-accent-900)
Gray (Neutral) Scale

.bg-gray-50 – background-color: var(--color-gray-50)
(Similarly .bg-gray-100 up to .bg-gray-900)
Semantic

.bg-success-500 – background-color: var(--color-success-500)
.bg-warning-500 – background-color: var(--color-warning-500)
.bg-error-500 – background-color: var(--color-error-500)
Background Attachment
.bg-fixed – background-attachment: fixed
.bg-local – background-attachment: local
.bg-scroll – background-attachment: scroll
Background Clip
.bg-clip-border – background-clip: border-box
.bg-clip-padding – background-clip: padding-box
.bg-clip-content – background-clip: content-box
.bg-clip-text – background-clip: text (+ -webkit-background-clip: text)
Background Position
.bg-left – background-position: left
.bg-center – background-position: center
.bg-right – background-position: right
.bg-top – background-position: top
.bg-bottom – background-position: bottom
(Additional combos like .bg-left-top, .bg-right-bottom, etc.)
Background Repeat
.bg-repeat – background-repeat: repeat
.bg-no-repeat – background-repeat: no-repeat
.bg-repeat-x – background-repeat: repeat-x
.bg-repeat-y – background-repeat: repeat-y
.bg-repeat-round – background-repeat: round
.bg-repeat-space – background-repeat: space
Background Size
.bg-auto – background-size: auto
.bg-cover – background-size: cover
.bg-contain – background-size: contain
Responsive Variants
.sm:bg-primary-500 – sets background-color: var(--color-primary-500) at min-width: var(--breakpoint-sm)
.md:bg-cover – sets background-size: cover at min-width: var(--breakpoint-md)
.lg:bg-center – sets background-position: center at min-width: var(--breakpoint-lg)
border.css
Border Widths & Styles
.border – border-style: solid, border-width: var(--border-width-normal)
.border-0 – border: 0
.border-thin – border-width: var(--border-width-thin), border-style: solid
.border-normal – border-width: var(--border-width-normal), border-style: solid
.border-thick – border-width: var(--border-width-thick), border-style: solid
Individual Sides

.border-t – top border only
.border-r – right border only
.border-b – bottom border only
.border-l – left border only
Border Style

.border-solid – border-style: solid
.border-dashed – border-style: dashed
.border-dotted – border-style: dotted
.border-double – border-style: double
Border Colors
(Expand for each color scale. Examples below:)

Primary Scale

.border-primary-50 – border-color: var(--color-primary-50)
(Similarly .border-primary-100 up to .border-primary-900)
Secondary Scale

.border-secondary-50 – border-color: var(--color-secondary-50)
(Similarly .border-secondary-100 up to .border-secondary-900)
Accent Scale

.border-accent-50 – border-color: var(--color-accent-50)
(Similarly .border-accent-100 up to .border-accent-900)
Gray (Neutral) Scale

.border-gray-50 – border-color: var(--color-gray-50)
(Similarly .border-gray-100 up to .border-gray-900)
Semantic

.border-success-500 – border-color: var(--color-success-500)
.border-warning-500 – border-color: var(--color-warning-500)
.border-error-500 – border-color: var(--color-error-500)
Border Radius
.rounded-none – border-radius: var(--radius-none)
.rounded-sm – border-radius: var(--radius-sm)
.rounded-md – border-radius: var(--radius-md)
.rounded-lg – border-radius: var(--radius-lg)
.rounded-full – border-radius: var(--radius-full)
(Individual corner classes like .rounded-t-sm can be similarly added.)

Responsive Variants
.sm:border-0 – removes border at min-width: var(--breakpoint-sm)
.md:border-accent-500 – sets accent border color at min-width: var(--breakpoint-md)
.lg:rounded-md – sets border-radius: var(--radius-md) at min-width: var(--breakpoint-lg)
Remember

All classes accept responsive prefixes.
For additional sets of corners or border widths, replicate the same naming patterns.
You can extend or reduce these classes based on your design’s needs.

effects.css
Box Shadows
.shadow-xs – box-shadow: var(--shadow-xs)
.shadow-sm – box-shadow: var(--shadow-sm)
.shadow-md – box-shadow: var(--shadow-md)
.shadow-lg – box-shadow: var(--shadow-lg)
.shadow-xl – box-shadow: var(--shadow-xl)
.shadow-2xl – box-shadow: var(--shadow-2xl)
.shadow-inner – box-shadow: var(--shadow-inner)
.shadow-none – box-shadow: none
Opacity
.opacity-0 – opacity: 0
.opacity-25 – opacity: 0.25
.opacity-50 – opacity: 0.5
.opacity-75 – opacity: 0.75
.opacity-100 – opacity: 1
Transitions
.transition-fast – transition: var(--transition-fast)
.transition-base – transition: var(--transition-base)
.transition-slow – transition: var(--transition-slow)
Transforms
.scale-0 – transform: scale(0)

.scale-50 – transform: scale(0.5)

.scale-75 – transform: scale(0.75)

.scale-90 – transform: scale(0.9)

.scale-100 – transform: scale(1)

.scale-105 – transform: scale(1.05)

.scale-110 – transform: scale(1.1)

.rotate-0 – transform: rotate(0deg)

.rotate-45 – transform: rotate(45deg)

.rotate-90 – transform: rotate(90deg)

.rotate-180 – transform: rotate(180deg)

.translate-x-0 – transform: translateX(0)

.translate-x-full – transform: translateX(100%)

.translate-y-0 – transform: translateY(0)

.translate-y-full – transform: translateY(100%)

Animations (Classes)
.animate-fadeIn – fadeIn 0.5s ease-in-out forwards
.animate-fadeOut – fadeOut 0.5s ease-in-out forwards
.animate-slideInLeft – slideInLeft 0.6s var(--transition-base) forwards
.animate-slideInRight – slideInRight 0.6s var(--transition-base) forwards
.animate-bounce – bounce 1s ease-in-out infinite
Keyframe Definitions (for reference)
@keyframes fadeIn – from opacity: 0 to opacity: 1
@keyframes fadeOut – from opacity: 1 to opacity: 0
@keyframes slideInLeft – from translateX(-100%) to 0
@keyframes slideInRight – from translateX(100%) to 0
@keyframes bounce – from translateY(0) to -25% (midpoint) back to 0
Responsive Variants
Use sm:, md:, lg: as needed, e.g.:

.sm:shadow-md – applies box-shadow: var(--shadow-md) at min-width: var(--breakpoint-sm)
.md:transition-base – applies transition: var(--transition-base) at min-width: var(--breakpoint-md)
.lg:animate-slideInLeft – applies slideInLeft animation at min-width: var(--breakpoint-lg)
flex-grid.css
Flexbox
Display

.flex – display: flex
.inline-flex – display: inline-flex
Flex Direction

.flex-row – flex-direction: row
.flex-row-reverse – flex-direction: row-reverse
.flex-col – flex-direction: column
.flex-col-reverse – flex-direction: column-reverse
Flex Wrap

.flex-wrap – flex-wrap: wrap
.flex-wrap-reverse – flex-wrap: wrap-reverse
.flex-nowrap – flex-wrap: nowrap
Justify Content

.justify-start – justify-content: flex-start
.justify-center – justify-content: center
.justify-end – justify-content: flex-end
.justify-between – justify-content: space-between
.justify-around – justify-content: space-around
.justify-evenly – justify-content: space-evenly
Align Items

.items-start – align-items: flex-start
.items-center – align-items: center
.items-end – align-items: flex-end
.items-baseline – align-items: baseline
.items-stretch – align-items: stretch
Align Content

.content-start – align-content: flex-start
.content-center – align-content: center
.content-end – align-content: flex-end
.content-between – align-content: space-between
.content-around – align-content: space-around
.content-evenly – align-content: space-evenly
Align Self

.self-auto – align-self: auto
.self-start – align-self: flex-start
.self-center – align-self: center
.self-end – align-self: flex-end
.self-stretch – align-self: stretch
Grid
Display

.grid – display: grid
.inline-grid – display: inline-grid
Grid Template Columns (1 to 12)

.grid-cols-1 – repeat(1, minmax(0, 1fr))
(Similarly .grid-cols-2 ... .grid-cols-12)
Grid Template Rows (1 to 6, extend as needed)

.grid-rows-1 – repeat(1, minmax(0, 1fr))
(Similarly .grid-rows-2 ... .grid-rows-6)
Grid Auto Flow

.grid-flow-row – grid-auto-flow: row
.grid-flow-col – grid-auto-flow: column
.grid-flow-dense – grid-auto-flow: dense
.grid-flow-row-dense – grid-auto-flow: row dense
.grid-flow-col-dense – grid-auto-flow: column dense
Gaps

.gap-0 – gap: var(--space-0)
.gap-1 – gap: var(--space-1)
.gap-2 – gap: var(--space-2)
.gap-3 – gap: var(--space-3)
.gap-4 – gap: var(--space-4)
.gap-5 – gap: var(--space-5)
.gap-6 – gap: var(--space-6)
.gap-7 – gap: var(--space-7)
.gap-8 – gap: var(--space-8)
.gap-9 – gap: var(--space-9)
.gap-10 – gap: var(--space-10)
Column Gap

.col-gap-0 – column-gap: var(--space-0)
(Similarly .col-gap-1 through .col-gap-10)
Row Gap

.row-gap-0 – row-gap: var(--space-0)
(Similarly .row-gap-1 through .row-gap-10)
Responsive Variants
.sm:grid-cols-2 – 2-column grid at min-width: var(--breakpoint-sm)
.md:flex-row – flex-direction: row at min-width: var(--breakpoint-md)
.lg:justify-between – justify-content: space-between at min-width: var(--breakpoint-lg)
(See file for complete lists. Extend for xl: or 2xl: if needed.)

misc.css
Cursor
.cursor-auto – cursor: auto
.cursor-default – cursor: default
.cursor-pointer – cursor: pointer
.cursor-wait – cursor: wait
.cursor-text – cursor: text
.cursor-move – cursor: move
.cursor-not-allowed – cursor: not-allowed
Pointer Events
.pe-none – pointer-events: none
.pe-auto – pointer-events: auto
User Select
.select-none – user-select: none
.select-text – user-select: text
.select-all – user-select: all
.select-auto – user-select: auto
Visibility
.visible – visibility: visible
.invisible – visibility: hidden
Display Toggle
.hidden – display: none (completely removes from layout)
Screen Reader Utilities
.sr-only – visually hidden, still accessible to screen readers
.not-sr-only – reverts .sr-only properties
Float
.float-left – float: left
.float-right – float: right
.float-none – float: none
Clearfix
.cf – adds a ::after table element to clear floated children
Text Overflow
.overflow-ellipsis – truncates text with ellipsis
.overflow-clip – truncates text with clip
Responsive Variants
.sm:hidden – sets display: none at min-width: var(--breakpoint-sm)
.md:cursor-not-allowed – sets cursor: not-allowed at min-width: var(--breakpoint-md)
.lg:select-none – sets user-select: none at min-width: var(--breakpoint-lg)
Tip:

You can combine classes, e.g., <div class="flex items-center justify-between bg-gray-100 p-4">.
For more breakpoints (xl:, 2xl:), replicate the same patterns.
Extend or remove utilities as your design system evolves.