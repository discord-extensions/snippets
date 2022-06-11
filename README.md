# Snippets
A collection of CSS / SCSS snippets that allow you to customize and enhance Discord.

## Support Server
If you're having an issue with any of the snippets, feel free to join the [support server](https://discord.gg/vYdXbEzqDs), or make an issue on this repository.

## Imports
<details>
<summary><b>Custom Message Colors</b></summary>

```scss
@import url('https://discord-extensions.github.io/snippets/custom-message-colors/custom-message-colors.css');

:root {
    /* || HSL Accent Values */
    --message-mentioned: 38, calc(var(--saturation-factor,1) * 96%), 54%;
    --message-replying: 235, calc(var(--saturation-factor,1) * 86%), 65%;
    --message-ephemeral: 235, calc(var(--saturation-factor,1) * 86%), 65%;
}
```
```scss
// || For more advanced customization, you can add on the variables below.

:root {
    /* || Advanced Coloring */
    --message-mentioned-indicator: hsl(var(--message-mentioned));
    --message-mentioned-background: hsla(var(--message-mentioned), 0.1);
    --message-mentioned-background-hover: hsla(var(--message-mentioned), 0.08);
    
    --message-replying-indicator: hsl(var(--message-replying));
    --message-replying-background: hsla(var(--message-replying), 0.05);
    --message-replying-background-hover: hsla(var(--message-replying), 0.1);

    --message-ephemeral-indicator: hsl(var(--message-ephemeral));
    --message-ephemeral-background: hsla(var(--message-ephemeral), 0.05);
    --message-ephemeral-background-hover: hsla(var(--message-ephemeral), 0.1);
}
```
</details>

<details>
<summary><b>Gradient Buttons</b></summary>

```scss
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
</details>

<details>
<summary><b>Windows Titlebar</b></summary>

```scss
@import url('https://discord-extensions.github.io/snippets/windows-titlebar/windows-titlebar.css');
```
</details>
