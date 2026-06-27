# CRENOVA Design System

## 1. Product

CRENOVA is a Korean app development studio landing page. The interface should feel precise, quiet, and technically capable, with restrained motion and clear contact paths.

## 2. Color

- `--bg` `#f5f4f0`: page background.
- `--bg-soft` `#fbfaf7`: soft section and menu surfaces.
- `--surface` `#ffffff`: elevated content surface.
- `--ink` `#15171c`: primary text and dark CTA fill.
- `--ink-inverse` `#ffffff`: text on dark CTA fill.
- `--ink-2` `#545a63`: secondary text and default nav links.
- `--ink-3` `#8b9099`: muted labels.
- `--ink-4` `#aeb2b8`: tertiary metadata.
- `--line` `#e6e4de`: default borders.
- `--line-soft` `#efeee9`: subtle dividers.

## 3. Typography

- Display: `Sora`, then `Pretendard`, then system sans.
- Body: `Inter`, then `Pretendard`, then system sans.
- Korean emphasis: `Pretendard`, then `Inter`, then system sans.
- Navigation labels use small Sora text with slight positive tracking.

## 4. Spacing

- Page gutter uses `--gut: clamp(20px, 5vw, 72px)`.
- Main content caps at `--maxw: 1200px`.
- Interactive controls use compact padding and clipped corners to match the angular brand language.

## 5. Components

- Header navigation is fixed, transparent at top, and gains a soft blurred surface after scroll.
- Standard nav links use `--ink-2`, then `--ink` on hover.
- Header CTA uses `--ink` background with `--ink-inverse` text in default, hover, and focus states.

## 6. Motion

- Navigation color and surface transitions should stay under 400ms.
- Interactive hover states may use opacity or transform, but must not animate layout properties.

## 7. Accessibility

- CTA text must preserve high contrast against dark fills in default, hover, and keyboard focus states.
- Korean text should use fonts with complete Hangul coverage and avoid clipping.
