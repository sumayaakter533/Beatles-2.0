# Beatles-2.0

Introducing Beatles 2.0 – the revamped version of the classic, now enhanced with Sass for better styling and advanced CSS techniques for a modern, polished, and responsive design. With features like Sass variables, mixins, Flexbox, CSS Grid, and smooth animations, the project is taken to a whole new level of performance and style.

---

## SASS Variables

1. Theme colors
   1. $primary
   2. $secondary
   3. $medium-dark
   4. $light
   5. $white

2. Spacing
   1. $base-padding
   2. $base-margin

3. Borders
   1. $base-border-thickness
   2. $base-border-radius

---

### SASS Utilities

```scss
'values': (
            '0': 0,
            '1': math.div($base-padding, 8),
            // 2px
            '2': math.div($base-padding, 4),
            // 4px
            '3': math.div($base-padding, 2),
            // 8px
            '4': $base-padding,
            // 16px
            '5': $base-padding * 1.25,
            // 20px
            '6': $base-padding * 1.5,
            // 24px
            '7': $base-padding * 1.75,
            // 28px
            '8': $base-padding * 2,
            // 32px
            '9': $base-padding * 2.5,
            // 40px
            '10': $base-padding * 3,
            // 48px
            '11': $base-padding * 3.5,
            // 56px
            '12': $base-padding * 4,
            // 64px
            '14': $base-padding * 5,
            // 80px
            '16': $base-padding * 6,
            // 96px
        ),
```
