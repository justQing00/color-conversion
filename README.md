# color-conversion
Color conversion for HEX to RGBA, HSL to RGBA, RGB to RGBA.
Gefault for get Hover color

### How to use
```javascript
import { getHoverRgbColor } from 'color-conversion';

getHoverRgbColor(HexColor || HSLColor || RGBColor, opacity)
// return `rgba(${rgba.r}, ${rgba.g}, ${rgba.b}, ${opacity || 0.65})`;

```