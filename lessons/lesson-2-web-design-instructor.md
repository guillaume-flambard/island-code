# Instructor Lesson Plan: Lesson 2
## Web Design Basics - Styling with CSS

---

## Overview & Learning Objectives

### Workshop Overview
Students will learn to style their HTML webpages using CSS (Cascading Style Sheets). They'll create a beautiful webpage for a local business (café, yoga studio, shop) with colors, fonts, spacing, and layout. This lesson builds on Lesson 1's HTML foundation.

### Learning Objectives
By the end of this workshop, students will be able to:
- Understand what CSS is and how it connects to HTML
- Create a separate CSS file and link it to HTML
- Use CSS properties: colors, fonts, spacing, backgrounds
- Style different HTML elements
- Customize colors to match a business theme
- Make a webpage mobile-friendly (responsive design)

### Prerequisites
- Completed Lesson 1 (basic HTML knowledge)
- Understanding of HTML tags and structure
- Comfortable creating and saving files

### Duration
**Total Time:** 90-120 minutes

---

## Preparation Checklist

### Before the Workshop
- [ ] Prepare example: plain HTML vs styled HTML
- [ ] Have business page template ready
- [ ] Test CSS file linking
- [ ] Prepare color palette examples
- [ ] Create sample styled webpage to show
- [ ] Test responsive design on mobile
- [ ] Have color picker tool ready (coolors.co)

### Materials Needed
- Student laptops
- Text editor with CSS syntax highlighting
- Web browser with developer tools
- Wi-Fi connection
- Sample business webpage (plain and styled versions)
- Color palette examples

### Setup Before Students Arrive
1. Display two versions: unstyled HTML vs styled webpage
2. Keep sample CSS file ready
3. Have business template HTML ready
4. Prepare color examples on screen

---

## Detailed Timing Breakdown

### Welcome & Review (5 minutes)
- Quick HTML review (2 min)
- Show before/after examples (3 min)

### Introduction to CSS (15 minutes)
- What is CSS explanation (5 min)
- CSS + HTML relationship (5 min)
- Introduction to CSS file structure (5 min)

### Create CSS File & Link It (15 minutes)
- Create style.css file (5 min)
- Link CSS to HTML (5 min)
- Test that it works (5 min)

### Styling Basics (30 minutes)
- Add colors (10 min)
- Add fonts and sizing (8 min)
- Add spacing (padding/margin) (7 min)
- Style lists and sections (5 min)

### Customization & Business Theme (20 minutes)
- Choose color palette (8 min)
- Apply colors to business (7 min)
- Customize for their business (5 min)

### Responsive Design (10 minutes)
- What is responsive design (3 min)
- Add mobile CSS (5 min)
- Test on mobile/small screen (2 min)

### Practice & Polish (10 minutes)
- Students customize their page (8 min)
- Final touches (2 min)

### Show & Share (10 minutes)
- Students share styled webpages (7 min)
- Wrap-up and questions (3 min)

### Buffer Time (5 minutes)

---

## Teaching Guide with Talking Points

### Part 1: Welcome & Review (5 minutes)

**Talking Points:**
- "Last time we built the skeleton - today we'll make it beautiful!"
- "Show of hands: Who finished their HTML webpage?"
- "Today we're styling a webpage for a business"

**Show Example:**
- Display plain HTML webpage (black text on white)
- Display same HTML with CSS (colors, fonts, layout)
- "Same HTML, but CSS makes it beautiful!"

**Bridge to CSS:**
- "HTML = structure, CSS = style"
- "Like a house: HTML is the frame, CSS is the paint"

---

### Part 2: Introduction to CSS (15 minutes)

**What is CSS?**
- "CSS = Cascading Style Sheets"
- "It's the language that makes websites look good"
- "CSS controls colors, fonts, spacing, layout"

**CSS + HTML Relationship:**
- "HTML creates the content"
- "CSS styles the content"
- "They work together!"

**Visual Explanation:**
- Show HTML: `<h1>Hello</h1>`
- Show CSS: `h1 { color: blue; }`
- Result: Blue heading

**CSS File Structure:**
```
selector {
    property: value;
}
```

**Example:**
```css
h1 {
    color: #FF6B6B;
    font-size: 2em;
}
```

**Translation:**
- "h1 = what we're styling (the heading)"
- "color = what we're changing"
- "#FF6B6B = the color (red)"
- "font-size = how big"
- "2em = twice normal size"

**Check Understanding:**
- "What styles what?"
- "In `p { color: green; }`, what turns green?"

---

### Part 3: Create CSS File & Link It (15 minutes)

**Step 1: Create CSS File (5 min)**
- "Let's create a new file"
- "Save it as 'style.css'"
- "Important: .css extension!"

**Step 2: Link CSS to HTML (5 min)**
- Show HTML `<head>` section
- Add: `<link rel="stylesheet" href="style.css">`
- "This connects your CSS to your HTML"
- "Like connecting a recipe to ingredients"

**Write Together:**
```html
<head>
    <meta charset="UTF-8">
    <title>Sunset Café</title>
    <link rel="stylesheet" href="style.css">
</head>
```

**Step 3: Test It Works (5 min)**
- Add simple CSS: `body { background-color: lightblue; }`
- Save CSS file
- Refresh HTML page
- "See? The background changed!"

**Common Mistake:**
- File not in same folder
- Wrong file name in link
- Forgot to save CSS file

**Help Troubleshooting:**
- Check file names match
- Check files in same folder
- Check browser console for errors

---

### Part 4: Styling Basics (30 minutes)

**Add Colors (10 min)**

**Talking Points:**
- "Colors make websites beautiful"
- "We can use color names or codes"

**Show Color Codes:**
- Named colors: `red`, `blue`, `green`
- Hex codes: `#FF6B6B` (red), `#4ECDC4` (teal)
- "Hex codes are more precise"

**Practice Together:**
```css
header {
    background-color: #FF6B6B;
    color: white;
}

section h2 {
    color: #4ECDC4;
}
```

**Explain:**
- `background-color` = background
- `color` = text color
- Walk around and help apply colors

**Add Fonts & Sizing (8 min)**

**Talking Points:**
- "Fonts change how text looks"
- "Sizes make things bigger or smaller"

**Practice:**
```css
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
}

h1 {
    font-size: 2.5em;
}
```

**Explain:**
- `font-family` = what font to use
- `font-size` = how big
- `em` = relative sizing (2em = 2x normal)

**Add Spacing (7 min)**

**Talking Points:**
- "Padding = space inside"
- "Margin = space outside"
- "Makes things not crowded"

**Visual:**
- Draw box on board
- Show padding inside, margin outside

**Practice:**
```css
section {
    padding: 30px;
    margin-bottom: 20px;
}
```

**Explain:**
- Numbers = pixels
- More padding = more space
- Walk around and help

**Style Lists & Sections (5 min)**

**Talking Points:**
- "Make lists look nice"
- "Add background colors to sections"

**Practice:**
```css
li {
    background-color: #F7F7F7;
    padding: 15px;
    margin-bottom: 10px;
}

section {
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}
```

**Explain:**
- `border-radius` = rounded corners
- `box-shadow` = shadow effect
- Makes it look modern

---

### Part 5: Customization & Business Theme (20 minutes)

**Choose Color Palette (8 min)**

**Talking Points:**
- "Different businesses need different colors"
- "Colors create feelings"

**Show Examples:**
- Café: Warm browns, oranges
- Yoga studio: Calm greens, blues
- Beach shop: Ocean blues, sands

**Tool:**
- Show coolors.co
- "Pick 3-4 colors that work together"
- "One main color, one accent, one neutral"

**Apply Colors (7 min)**

**Talking Points:**
- "Put your colors in CSS"
- "Main color for header"
- "Accent color for headings"
- "Neutral for background"

**Practice:**
- Students choose colors
- Apply to their webpage
- Walk around and help

**Customize for Their Business (5 min)**

**Talking Points:**
- "Make it match your business"
- "Change menu items"
- "Update location and hours"

**Encourage:**
- "Make it yours!"
- "Experiment with colors"
- "See what looks good"

---

### Part 6: Responsive Design (10 minutes)

**What is Responsive? (3 min)**

**Talking Points:**
- "Websites look different on phones vs computers"
- "Responsive = works on all devices"
- "Most people use phones!"

**Show Example:**
- Same webpage on computer vs phone
- "See how it adjusts?"

**Add Mobile CSS (5 min)**

**Introduce Media Query:**
```css
@media (max-width: 600px) {
    header h1 {
        font-size: 1.8em;
    }
    
    section {
        padding: 20px;
    }
}
```

**Explain:**
- `@media` = "when screen is small"
- `max-width: 600px` = "phones"
- Changes CSS for mobile

**Test on Mobile (2 min)**

**Action:**
- Resize browser window
- See how it changes
- Test on actual phone if possible

---

### Part 7: Practice & Polish (10 minutes)

**Talking Points:**
- "Now make it perfect!"
- "Add your finishing touches"
- "Experiment and have fun!"

**Walk Around:**
- Help with specific issues
- Answer questions
- Give suggestions

**Encouragement:**
- "Looks great!"
- "Try this color!"
- "You're doing amazing!"

---

### Part 8: Show & Share (10 minutes)

**Talking Points:**
- "Let's see your beautiful webpages!"
- "Everyone did something amazing"

**Sharing:**
- 2-3 students show their webpage
- Point out what they did well
- Celebrate their work

**Wrap-Up:**
- "Today you learned CSS!"
- "Your webpages look professional"
- "Next time: Publishing online!"

**Questions:**
- "What was hardest?"
- "What's your favorite part?"
- "What do you want to learn next?"

---

## Common Issues & Solutions

### Issue: CSS not applying
**Symptoms:** Changes don't appear in browser
**Solutions:**
- Check CSS file is saved
- Check link in HTML is correct: `<link rel="stylesheet" href="style.css">`
- Check file names match exactly
- Check files in same folder
- Hard refresh browser (Ctrl+Shift+R)

### Issue: Colors look wrong
**Symptoms:** Expected color doesn't appear
**Solutions:**
- Check color code spelling (#FF6B6B, not #FF6B6B)
- Check for typos: `color:` not `colour:`
- Try named color first: `red`, `blue`
- Use color picker tool

### Issue: Spacing too much/too little
**Symptoms:** Elements too close or far apart
**Solutions:**
- Adjust padding/margin numbers
- Start with small numbers (10px, 20px)
- Experiment to see what looks good

### Issue: Font not changing
**Symptoms:** Font stays default
**Solutions:**
- Check font-family spelling
- Use common fonts: Arial, Georgia, Times
- Check for typos in CSS

### Issue: Responsive not working
**Symptoms:** Mobile version looks broken
**Solutions:**
- Check media query syntax
- Make sure `@media` is at end of CSS file
- Test by resizing browser window
- Check for typos in media query

### Issue: CSS overwhelming
**Symptoms:** Student frustrated with CSS complexity
**Solutions:**
- Start with just colors
- Add one property at a time
- Provide template to start
- Pair with helper student

---

## Differentiation Strategies

### For Beginners
- **Start simple:** Just colors first
- **Use template:** Give pre-written CSS
- **One property at a time:** Don't overwhelm
- **Visual examples:** Show lots of examples
- **Pair programming:** Work with helper

**Modifications:**
- Focus on 3-4 CSS properties only
- Use named colors (red, blue) not codes
- Skip responsive design initially

### For Intermediate Students
- **More properties:** Add borders, shadows
- **Customization:** Experiment freely
- **Help others:** Become CSS helpers
- **Advanced:** Learn CSS grid/flexbox basics

**Extensions:**
- Google Fonts integration
- Transitions and hover effects
- Background images
- Multiple color schemes

### For Advanced Students
- **Complex layouts:** Grid, flexbox
- **Animations:** CSS animations
- **Teaching:** Help explain concepts
- **Projects:** Create style guide

**Advanced Topics:**
- CSS variables
- Media queries (advanced)
- CSS frameworks introduction
- Preprocessors (SASS) preview

### For Language Barriers
- **Visual demonstration:** Show, don't just tell
- **Color examples:** Show color swatches
- **Simple terms:** "make it red" not "apply color property"
- **Hands-on:** Let them experiment

---

## Assessment Checkpoints

### After Part 3 (Linking CSS)
**Check:**
- [ ] Can students create CSS file?
- [ ] Can they link it to HTML?
- [ ] Do CSS changes appear?

**If not:** Review linking, check file locations

### After Part 4 (Styling Basics)
**Check:**
- [ ] Can students add colors?
- [ ] Can they change fonts?
- [ ] Do they understand selectors?

**If not:** Review CSS syntax, provide examples

### After Part 5 (Customization)
**Check:**
- [ ] Can students customize colors?
- [ ] Can they style their business page?
- [ ] Are they comfortable experimenting?

**If not:** Provide color palette, simplify choices

### Final Checkpoint
**Students should be able to:**
- [ ] Create and link CSS file
- [ ] Style HTML elements
- [ ] Customize colors for business
- [ ] Make basic responsive design

**If struggling:** Provide template, focus on core concepts

---

## Wrap-Up & Next Steps

### Recap (2 minutes)
**Key Points:**
- "CSS makes websites beautiful"
- "CSS file links to HTML"
- "Colors, fonts, spacing = style"
- "Responsive = works on mobile"

### Homework/Follow-Up (Optional)
- **Practice:** Change colors 5 times, see what looks best
- **Challenge:** Add Google Fonts
- **Explore:** Look at other websites, right-click → Inspect → See CSS

### Next Workshop Preview
- "Next time: Publishing your website online!"
- "We'll use GitHub Pages"
- "Everyone will see your website!"

### Resources to Share
- Student guide: `workshops/workshop-2-web-design.md`
- Template: `templates/business-page-template.html` and `business-page-style.css`
- Color tool: coolors.co
- Google Fonts: fonts.google.com

---

## Additional Notes

### Timing Adjustments
- **Short on time:** Skip responsive design, focus on colors
- **Extra time:** Add more CSS properties, experiment more

### Cultural Considerations
- Respect color preferences
- Celebrate local business themes
- Encourage Thai/Burmese text styling

### Energy Management
- CSS can be frustrating - stay positive
- Celebrate small wins
- Take breaks if needed
- End with success sharing

---

**Remember:** CSS is about experimentation! Encourage students to try things and see what happens! 🎨

