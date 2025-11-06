# Workshop 2: Web Design Basics

## Create a Beautiful Page for a Local Café or Yoga Studio

**Duration:** 1.5 - 2 hours  
**Difficulty:** Beginner  
**What you'll learn:** CSS styling, colors, fonts, layout basics

---

## What We're Building

A styled webpage for a local business (café, yoga studio, shop, etc.) with colors, fonts, and a nice layout.

---

## Step 1: Start with HTML Structure

Create a new file called `business-page.html` and add this structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunset Café - Koh Phangan</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Sunset Café</h1>
        <p>Fresh coffee and amazing views in Koh Phangan</p>
    </header>
    
    <main>
        <section>
            <h2>Welcome</h2>
            <p>Come enjoy the best coffee on the island with stunning sunset views.</p>
        </section>
        
        <section>
            <h2>Our Menu</h2>
            <ul>
                <li>Coffee - 50 THB</li>
                <li>Fresh Juice - 60 THB</li>
                <li>Traditional Thai Tea - 45 THB</li>
            </ul>
        </section>
        
        <section>
            <h2>Visit Us</h2>
            <p>Open daily 8am - 8pm</p>
            <p>Near Haad Rin Beach</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2024 Sunset Café</p>
    </footer>
</body>
</html>
```

**Change it for your business:**
- Replace "Sunset Café" with your business name
- Update the menu items and prices
- Change the location and hours

---

## Step 2: Create Your CSS File

Create a new file called `style.css` in the same folder.

---

## Step 3: Add Colors

Add these styles to your `style.css` file:

```css
/* Body and basic styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    margin: 0;
    padding: 0;
}

/* Header */
header {
    background-color: #FF6B6B;
    color: white;
    padding: 40px 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

/* Main content */
main {
    max-width: 800px;
    margin: 0 auto;
    padding: 40px 20px;
}

section {
    margin-bottom: 40px;
}

section h2 {
    color: #4ECDC4;
    border-bottom: 3px solid #FFE66D;
    padding-bottom: 10px;
}

/* Footer */
footer {
    background-color: #2C3E50;
    color: white;
    text-align: center;
    padding: 20px;
}
```

---

## Step 4: Customize Your Colors

Choose colors that match your business:

**Color ideas:**
- Café: Warm browns, oranges (#D2691E, #FF8C00)
- Yoga Studio: Calm greens, blues (#90EE90, #87CEEB)
- Beach Shop: Ocean blues, sand colors (#4682B4, #F4A460)

**How to change colors:**
- Find colors you like at [coolors.co](https://coolors.co)
- Replace the color codes (like `#FF6B6B`) in your CSS

---

## Step 5: Make Lists Look Nice

Add this to your CSS:

```css
ul {
    list-style: none;
    padding: 0;
}

li {
    background-color: #F7F7F7;
    padding: 15px;
    margin-bottom: 10px;
    border-left: 4px solid #FF6B6B;
}
```

---

## Step 6: Add Some Spacing

Make everything look cleaner:

```css
section {
    background-color: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    margin-bottom: 30px;
}
```

---

## Step 7: Make It Responsive (Mobile-Friendly)

Add this at the end of your CSS:

```css
/* For mobile phones */
@media (max-width: 600px) {
    header h1 {
        font-size: 1.8em;
    }
    
    main {
        padding: 20px 10px;
    }
    
    section {
        padding: 20px;
    }
}
```

---

## CSS Properties We Learned

- `background-color` - Changes background color
- `color` - Changes text color
- `padding` - Adds space inside an element
- `margin` - Adds space outside an element
- `border-radius` - Makes rounded corners
- `box-shadow` - Adds shadow effects
- `font-family` - Changes the font
- `@media` - Makes it work on mobile

---

## Challenge (Optional)

Try adding:
- A background image
- Different fonts from Google Fonts
- Hover effects on menu items
- A contact form

---

## What's Next?

You've styled your webpage! In the next workshop, we'll learn how to put it online so everyone can see it.

---

## Questions?

Ask your instructor or experiment with different colors and styles!

