# Gradient Buttons

## Importing
```css
@import url('https://discord-extensions.github.io/snippets/gradient-buttons/gradient-buttons.css');

:root {
    /* || Gradients */
    --gradient-special: 140deg, hsl(245, calc(var(--saturaton-factor, 1)*79%), 72%) 0%, hsl(287, calc(var(--saturaton-factor, 1)*80%), 70%) 100%;
    --gradient-blurple: 140deg, hsl(235, calc(var(--saturation-factor, 1)*85%), 72%) 0%, hsl(235, calc(var(--saturation-factor, 1)*85%), 60%) 100%;
    --gradient-green: 140deg, hsl(139, calc(var(--saturaton-factor, 1)*47%), 44%) 0%, hsl(139, calc(var(--saturaton-factor, 1)*66%), 24%) 100%;
    --gradient-yellow: 140deg, hsl(38, calc(var(--saturaton-factor, 1)*96%), 54%) 0%, hsl(38, calc(var(--saturaton-factor, 1)*82%), 41%) 100%;
    --gradient-red: 140deg, hsl(359, calc(var(--saturaton-factor, 1)*83%), 59%) 0%, hsl(359, calc(var(--saturaton-factor, 1)*54%), 37%) 100%;
    --gradient-grey: 140deg, hsl(214, calc(var(--saturaton-factor, 1)*10%), 50%) 0%, hsl(216, calc(var(--saturaton-factor, 1)*11%), 26%) 100%;

    /* || Transitions */
    --button-transition: 0.1s linear;
    --font-default: 500;
    --font-hover: 525;
    --fontsize-hover: 15px;
    --transform-normal: scale(1);
    --transform-hover: scale(1.15);
    --button-transform-hover: scale(1.04);
}
```