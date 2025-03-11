root.css
Note: root.css does not provide utility classes.
It defines design tokens (custom properties) used by other modules. Below is a quick reference for each token's primary purpose or value.

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

Animations
.animate-fadeIn – fadeIn animation
.animate-fadeOut – fadeOut animation
.animate-slideInLeft – slideInLeft animation
.animate-slideInRight – slideInRight animation
.animate-bounce – bounce animation

flex-grid.css
Flexbox Display
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

Flex Properties
.flex-1 – flex: 1 1 0%
.flex-auto – flex: 1 1 auto
.flex-initial – flex: 0 1 auto
.flex-none – flex: none

Flex Grow/Shrink
.flex-grow-0 – flex-grow: 0
.flex-grow – flex-grow: 1
.flex-shrink-0 – flex-shrink: 0
.flex-shrink – flex-shrink: 1

Flex Basis
.flex-basis-0 – flex-basis: 0
.flex-basis-auto – flex-basis: auto
.flex-basis-full – flex-basis: 100%

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

Grid Display
.grid – display: grid
.inline-grid – display: inline-grid

Grid Template Columns
.grid-cols-1 through .grid-cols-12 – grid-template-columns: repeat(n, minmax(0, 1fr))

Grid Column Start/End
.col-span-1 through .col-span-12 – grid-column: span n / span n
.col-start-1 through .col-start-13 – grid-column-start: n
.col-end-1 through .col-end-13 – grid-column-end: n

Grid Template Rows
.grid-rows-1 through .grid-rows-6 – grid-template-rows: repeat(n, minmax(0, 1fr))

Grid Row Start/End
.row-span-1 through .row-span-6 – grid-row: span n / span n
.row-start-1 through .row-start-7 – grid-row-start: n
.row-end-1 through .row-end-7 – grid-row-end: n

Grid Flow
.grid-flow-row – grid-auto-flow: row
.grid-flow-col – grid-auto-flow: column
.grid-flow-dense – grid-auto-flow: dense
.grid-flow-row-dense – grid-auto-flow: row dense
.grid-flow-col-dense – grid-auto-flow: column dense

Gap
.gap-0 through .gap-10 – gap: var(--space-n)
.gap-x-0 through .gap-x-10 – column-gap: var(--space-n)
.gap-y-0 through .gap-y-10 – row-gap: var(--space-n)

misc.css
Cursor Types
.cursor-auto – cursor: auto
.cursor-default – cursor: default
.cursor-pointer – cursor: pointer
.cursor-wait – cursor: wait
.cursor-text – cursor: text
.cursor-move – cursor: move
.cursor-help – cursor: help
.cursor-not-allowed – cursor: not-allowed
(Plus many more cursor variants)

Pointer Events
.pointer-events-none – pointer-events: none
.pointer-events-auto – pointer-events: auto
.pointer-events-all – pointer-events: all
(Plus additional pointer-events variants)

User Select
.select-none – user-select: none
.select-text – user-select: text
.select-all – user-select: all
.select-auto – user-select: auto
.select-contain – user-select: contain

Resize
.resize-none – resize: none
.resize – resize: both
.resize-y – resize: vertical
.resize-x – resize: horizontal

List Style
.list-none – list-style-type: none
.list-disc – list-style-type: disc
.list-decimal – list-style-type: decimal
.list-inside – list-style-position: inside
.list-outside – list-style-position: outside

Screen Readers
.sr-only – Visually hidden but accessible to screen readers
.not-sr-only – Reverts sr-only properties

Visibility
.visible – visibility: visible
.invisible – visibility: hidden
.collapse – visibility: collapse
.hidden – display: none

Box Decoration Break
.decoration-slice – box-decoration-break: slice
.decoration-clone – box-decoration-break: clone

Box Sizing
.box-border – box-sizing: border-box
.box-content – box-sizing: content-box

Float & Clear
.float-left – float: left
.float-right – float: right
.float-none – float: none
.clear-left – clear: left
.clear-right – clear: right
.clear-both – clear: both
.clear-none – clear: none

Object Fit & Position
.object-contain – object-fit: contain
.object-cover – object-fit: cover
.object-fill – object-fit: fill
.object-none – object-fit: none
.object-scale-down – object-fit: scale-down

Mix Blend Mode
.mix-blend-normal – mix-blend-mode: normal
.mix-blend-multiply – mix-blend-mode: multiply
(Plus additional blend mode variants)

Responsive Variants
All utilities can be prefixed with:
sm: – @media (min-width: var(--breakpoint-sm))
md: – @media (min-width: var(--breakpoint-md))
lg: – @media (min-width: var(--breakpoint-lg))

Example:
.sm:flex – display: flex at sm breakpoint
.md:grid-cols-2 – 2-column grid at md breakpoint
.lg:justify-between – justify-content: space-between at lg breakpoint