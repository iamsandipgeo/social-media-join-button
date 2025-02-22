# WhatsApp and Telegram Group Join Buttons

This project provides a responsive and animated WhatsApp and Telegram group join button for your Blogger site. The buttons are designed to be visually appealing and functional, with hover animations and a ripple effect on click.

## Features

- **Responsive Design**: Buttons adjust to different screen sizes, stacking vertically on mobile devices.
- **Animated Icons**: Icons rotate 360 degrees on hover.
- **Ripple Effect**: A ripple effect appears when the buttons are clicked.
- **Customizable**: Easily change colors, icons, and text to match your blog's theme.

## How to Use

1. **Copy the Code**:
   - Copy the HTML, CSS, and JavaScript code provided in the `index.html` file.

2. **Add to Blogger**:
   - Go to your Blogger Dashboard.
   - Navigate to **Theme** > **Edit HTML**.
   - Paste the code where you want the buttons to appear (e.g., inside a `<div>` in your post, sidebar, or footer).

3. **Replace Links**:
   - Replace `https://wa.me/yourwhatsapplink` with your actual WhatsApp group link.
   - Replace `https://t.me/yourtelegramlink` with your actual Telegram group link.

4. **Save and View**:
   - Save the changes and view your blog to see the buttons in action.

## Code Structure

- **HTML**: Defines the structure of the buttons.
- **CSS**: Styles the buttons and adds animations.
- **JavaScript**: Adds a ripple effect on button click.

## Example

```html
<div class="social-buttons">
  <a href="https://wa.me/yourwhatsapplink" class="whatsapp-button" target="_blank">
    <span class="icon">💬</span>
    <span class="text">Join WhatsApp Group</span>
  </a>
  <a href="https://t.me/yourtelegramlink" class="telegram-button" target="_blank">
    <span class="icon">📢</span>
    <span class="text">Join Telegram Group</span>
  </a>
</div>
