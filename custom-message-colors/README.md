# Custom Message Colors
Customize mentions, replying, and emphermal messages.

## Customization
Colors use HSL values to remain compatible with a Discord accessibility feature. It is not required to leave `calc(var(--saturation-factor,1)*%)` in the variable, but you must use the HSL color format values.

## Importing
```css
@import url('https://discord-extensions.github.io/snippets/custom-message-colors/custom-message-colors.css');

:root {
    /* || HSL Accent Values */
    --message-mentioned: 38, calc(var(--saturation-factor,1) * 96%), 54%;
    --message-replying: 235, calc(var(--saturation-factor,1) * 86%), 65%;
    --message-ephemeral: 235, calc(var(--saturation-factor,1) * 86%), 65%;
}
```
For more advanced customization, you can add on the variables below.
```css
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