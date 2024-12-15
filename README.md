# Anki-style
Add color to anki by this template 


# Anki Card Styling

This repository contains custom CSS styles for Anki cards, designed to enhance the visual appeal and readability of your
flashcards. The styles are based on modifications inspired by the [Anki CSS Styling Guide](https://www.tumblr.com/heibaibufen/162592016144/anki-css-styling-creating-beautiful-cards?redirect_to=%2Fheibaibufen%2F162592016144%2Fanki-css-styling-creating-beautiful-cards&source=blog_view_login_wall).

Please, if you do not know what to do, first look at the above link. 

## Files Included

- `style.css`: The main CSS file containing all the custom styles for Anki cards.

## Overview

The CSS styles in this  repository include:
- **Card Background**:  Custom background images and colors.
- **Text Formatting**:  Different styles for text, including font size, color, and alignment.
- **Enclosures**:       Styled boxes for text with padding, background colors, and borders.
- **Mobile View**:      Adjustments for better display on mobile devices.
- **Special Elements**: Styles for categories, blanked words, underlined text, and more.

## Example Styles

```css
.card {
    font: 1.5em/1.5 sans-serif;
    text-align: center;
    background-image: url("_10.png");
    background-position: center top;
}

.mobile .card {
    margin: 15px 15px 50px 15px;
}

#encl {
    padding: 35px 20px 24px 20px;
    background-color: #fff;
    border-radius: 16px;
    overflow: hidden;
    border-left: 5px solid #47c4f1;
    border-bottom: 5px solid #A1A6BC;
}

/* Further styles... */
```

## How to Use

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/anki-card-styling.git
   ```

2. Copy the `style.css` file's content to your Anki collection media folder.
3. Apply the styles to your Anki cards by editing the card templates. 

## Customization

You can customize the styles by editing the `style`. Here are some notes for customization:
- Change the background color or image by modifying the `background-image` and `background-color` properties.
- Adjust padding, margins, and borders to fit your preferences.
- Modify text styles, including font size, color, and alignment.

## Feedback

Feedback is welcome! Feel free to open an issue or contact me directly with any suggestions or questions.

---

Feel free to adjust the content as needed! If you need further assistance, just let me know.