# Slider

## Overview

A customizable and interactive slider, implemented in HTML, CSS, and JavaScript. The slider allows users to navigate through slides, automatically transition between slides, and toggle additional information for each slide.

![Demo](demo/IMG_20240126_091925.jpg)
![Demo](demo/IMG_20240126_091949.jpg)
![Demo](demo/IMG_20240126_091957.jpg)
![Demo](demo/IMG_20240126_092016.jpg)

## Features

1. **Slide Navigation:**
   - Users can navigate through slides using dedicated navigation controls.
   - Clicking on a navigation control triggers a smooth transition to the corresponding slide.

2. **Auto Sliding:**
   - The slider supports automatic transitioning between slides.
   - Users can customize the auto-sliding behavior, including enabling/disabling it and setting the delay between transitions.

3. **Block Auto Sliding After Click:**
   - Optionally, users can configure the slider to temporarily block auto-sliding after a manual navigation click.

4. **Demo Container Interaction:**
   - Each slide includes an action button that, when clicked, reveals additional information in the demo container.
   - A close button allows users to hide the additional information.

5. **Global Blending Activation:**
   - The slider supports the activation of global blending, enhancing the visual appeal.

## Usage

1. **HTML Structure:**
   - Include the necessary HTML structure for the slider, including slides and navigation controls.

2. **CSS Styling:**
   - Apply the provided CSS styles to ensure a visually appealing and consistent slider appearance.

3. **JavaScript Initialization:**
   - Initialize the slider using the provided JavaScript code, specifying the target selector and any desired options.

4. **Options:**
   - Customize the slider behavior by adjusting options such as auto-sliding, auto-sliding delay, and blocking auto-sliding after user clicks.

5. **Additional Interactivity:**
   - Optionally, implement additional interactivity such as revealing credits or activating global blending.

## Example Initialization

```javascript
// Initialize the slider on elements with the class ".example-slider"
fncSlider(".example-slider", { autoSlidingDelay: 4000 });
```

## Demo

For a live demonstration, visit [Demo](https://johndev19.github.io/Animated-Slider/)

## Credits

This slider implementation was created by *JohnDev19 (John Ré Poras)*. Feel free to explore and modify the code to suit your project's needs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
