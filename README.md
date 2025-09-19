# Responsive Layout – Boolean Academy

This exercise didn’t require building the website from scratch, but rather adding **responsiveness** to the existing layout, **without modifying the given HTML or CSS**.  
The work focused exclusively on using **media queries**.

🌐 [Check it out!](https://michecosa.github.io/html-css-resp-wannabe/)

<br>

## Goals Achieved

- **Tablet (≤ 768px)**  
  - Columns (`.col`) expand to full width.  
  - *Lessons* and *Steps* sections display one card per row.  
  - In the *Why Us* section, the image and text are stacked vertically (image above, text below).  

- **Smartphone (≤ 480px)**  
  - Forced column layout with `flex-direction: column`.  
  - Every element is stacked one after another.  
  - Resized headings (`h1`, `h2`, `h3`) for better readability.  
  - Added extra spacing between elements.  

- **Between 769px and 1160px**  
  - Fixed the issue of a too rigid layout.  
  - Removed the horizontal scrollbar by resizing `.container` to `width: 100%` .  
