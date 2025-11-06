# Instructor Lesson Plan: Lesson 1
## "Hello Koh Phangan" - Build Your First Website

---

## Overview & Learning Objectives

### Workshop Overview
Students will create their first HTML webpage - a simple personal webpage introducing themselves and their connection to Koh Phangan. This foundational lesson introduces HTML structure, basic tags, and the concept of viewing web pages in a browser.

### Learning Objectives
By the end of this workshop, students will be able to:
- Understand what HTML is and its basic structure
- Create an HTML file using a text editor
- Use basic HTML tags: `<h1>`, `<h2>`, `<p>`, `<ul>`, `<li>`, `<a>`
- Save and view their webpage in a web browser
- Customize content with their own information
- Add links to their webpage

### Prerequisites
- Basic computer skills (creating folders, saving files)
- Access to a text editor (VS Code recommended)
- Access to a web browser

### Duration
**Total Time:** 90-120 minutes

---

## Preparation Checklist

### Before the Workshop
- [ ] Test text editor installation on your laptop
- [ ] Prepare example HTML file to show students
- [ ] Have template file ready (`templates/hello-world-template.html`)
- [ ] Test opening HTML files in browser
- [ ] Prepare backup internet connection (hotspot)
- [ ] Print student workshop guide (optional but helpful)
- [ ] Have extra USB drives with template files
- [ ] Check all student laptops can access text editor

### Materials Needed
- Student laptops (or ask them to bring their own)
- Text editor installed (VS Code, Notepad++, or TextEdit)
- Web browser (Chrome, Firefox, or Safari)
- Wi-Fi connection
- Projector or large screen (optional)
- Extension cords and chargers

### Setup Before Students Arrive
1. Write example HTML on screen/board
2. Keep sample webpage open in browser
3. Have workshop file ready to share
4. Test saving/opening HTML files

---

## Detailed Timing Breakdown

### Welcome & Setup (10 minutes)
- Introductions (3 min)
- Explain what we're building (2 min)
- Set up workspace - open text editor (5 min)

### Introduction to HTML (15 minutes)
- What is HTML explanation (5 min)
- Show example webpage (3 min)
- Basic structure explanation (7 min)

### Hands-On: Creating HTML File (25 minutes)
- Create file and folder (5 min)
- Write basic HTML structure (10 min)
- Add content (10 min)

### View Your Website (10 minutes)
- Save file (2 min)
- Open in browser (3 min)
- Refresh to see changes (5 min)

### Adding More Content (20 minutes)
- Add headings and paragraphs (8 min)
- Add lists (7 min)
- Add links (5 min)

### Practice & Customization (15 minutes)
- Personalize their webpage (10 min)
- Experiment with tags (5 min)

### Show & Share (10 minutes)
- Students share their webpages (7 min)
- Questions and wrap-up (3 min)

### Buffer Time (5 minutes)
- For questions, troubleshooting, or slower pace

---

## Teaching Guide with Talking Points

### Part 1: Welcome & Setup (10 minutes)

**Talking Points:**
- "Welcome to Island Code for Locals! Today we're making your first website."
- "Does everyone have a laptop? Can everyone see the screen?"
- "We're going to build something simple that you can show your friends!"

**Action:**
- Check everyone has necessary tools
- Open text editor together
- Create a folder called "my-first-website"

**Questions to Ask:**
- "Has anyone made a website before?" (Expect mostly no)
- "What do you think a website is made of?"

---

### Part 2: Introduction to HTML (15 minutes)

**Talking Points:**
- "HTML stands for HyperText Markup Language - it's the language websites speak."
- "Think of HTML like the skeleton of a webpage - it gives it structure."
- "We write HTML in a text editor, then the browser shows it as a webpage."

**Show Example:**
- Display a simple HTML file in text editor
- Show the same file opened in browser
- Point out: "This code becomes this webpage"

**Explain Basic Structure:**
```
<!DOCTYPE html> - Tells browser this is HTML
<html> - The container for everything
<head> - Information about the page (not shown)
<body> - What people see on the page
```

**Visual Aid:**
- Draw HTML structure on board
- Use analogy: HTML = bones, CSS (later) = clothes

**Check for Understanding:**
- "Can someone tell me what goes in the <body>?"
- "What's the difference between <head> and <body>?"

---

### Part 3: Hands-On: Creating HTML File (25 minutes)

**Step-by-Step Instructions:**

**Step 1: Create File (5 min)**
- "Let's create a new file together"
- "File → New File"
- "Save it as 'index.html' in your folder"
- Emphasize: ".html" extension is important!

**Step 2: Write Basic Structure (10 min)**
- Write together, line by line
- Use example:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Hello Koh Phangan!</title>
</head>
<body>
    <h1>Hello Koh Phangan!</h1>
    <p>My name is [Your Name]</p>
</body>
</html>
```

**Talking Points:**
- "Let's write this together, line by line"
- "The <h1> tag makes big text - like a title"
- "The <p> tag makes a paragraph"
- "Notice: every opening tag has a closing tag with /"

**Common Mistakes to Watch For:**
- Missing closing tags
- Wrong file extension (.txt instead of .html)
- Not saving file

**Step 3: Add Content (10 min)**
- "Now replace [Your Name] with your actual name"
- "Add more sentences about yourself"
- Walk around and help students

**Encouragement:**
- "There's no right or wrong here - make it yours!"
- "If something breaks, we can fix it together!"

---

### Part 4: View Your Website (10 minutes)

**Talking Points:**
- "Now let's see your webpage!"
- "Browsers are like translators - they read HTML and show it as a webpage"

**Steps:**
1. Save the file (Ctrl+S / Cmd+S)
2. Find file in folder
3. Double-click (or right-click → Open with → Browser)
4. "Look! Your webpage!"

**Key Point:**
- "To see changes, save file, then refresh browser (F5)"
- Demonstrate making a change, saving, refreshing

**Encouragement:**
- "Everyone should see 'Hello Koh Phangan!' on their screen!"
- Celebrate first webpage!

---

### Part 5: Adding More Content (20 minutes)

**Introduce New Tags:**

**Headings (8 min):**
- Show `<h1>`, `<h2>`, `<h3>` - different sizes
- "h1 is biggest, h6 is smallest"
- Have them add a heading

**Lists (7 min):**
- Show `<ul>` (unordered list) and `<li>` (list item)
- "Like a shopping list"
- Example: List of things they love about Koh Phangan
- Write together:
```html
<ul>
    <li>The beautiful beaches</li>
    <li>The friendly community</li>
</ul>
```

**Links (5 min):**
- Show `<a href="URL">Text</a>`
- "Links connect pages together"
- Have them add a link to favorite place
- Explain: href = where it goes, text = what you click

**Practice:**
- Walk around and help
- Answer questions
- Encourage experimentation

---

### Part 6: Practice & Customization (15 minutes)

**Talking Points:**
- "Now make it yours! Add more about yourself"
- "Try different tags - see what happens!"
- "If something breaks, raise your hand - we'll fix it together"

**Suggestions:**
- Add more paragraphs
- Add more headings
- Add more links
- Experiment with different tags

**Walk Around:**
- Help students individually
- Fix mistakes together
- Encourage creativity

**Advanced Students:**
- Challenge: Add an email link (`mailto:`)
- Challenge: Add an image tag (introduce `<img>`)

---

### Part 7: Show & Share (10 minutes)

**Talking Points:**
- "Let's see what everyone created!"
- "Everyone did something amazing today"

**Sharing:**
- Ask 2-3 volunteers to show their webpage
- Point out what they did well
- Celebrate their work

**Wrap-Up:**
- "Today you made your first website!"
- "Next time, we'll make it look beautiful with colors"

**Questions:**
- "What did you learn?"
- "What was the hardest part?"
- "What do you want to learn next?"

---

## Common Issues & Solutions

### Issue: File won't open in browser
**Symptoms:** Double-clicking does nothing or opens in text editor
**Solution:**
- Right-click → "Open with" → Choose browser
- Make sure file extension is .html (not .txt)
- Drag file into browser window

### Issue: Can't see changes after editing
**Symptoms:** Changes don't appear in browser
**Solution:**
- Make sure you saved the file (Ctrl+S)
- Refresh browser (F5 or Ctrl+R)
- Sometimes need hard refresh (Ctrl+Shift+R)

### Issue: Page looks broken/weird
**Symptoms:** Text all jumbled, tags showing
**Solution:**
- Check for missing closing tags (`</p>`, `</h1>`, etc.)
- Check for typos in tag names
- Look for missing `<` or `>` characters

### Issue: Links don't work
**Symptoms:** Clicking link does nothing
**Solution:**
- Check URL has `http://` or `https://`
- Check quotes around URL: `href="URL"`
- Test link in browser first

### Issue: Can't find file
**Symptoms:** Saved file but can't find it
**Solution:**
- Check "Downloads" folder
- Check Desktop
- Use "Save As" and choose specific location
- Show them how to use File Explorer/Finder

### Issue: Text editor too complicated
**Symptoms:** Student overwhelmed by VS Code
**Solution:**
- Use simpler editor (Notepad, TextEdit)
- Hide sidebars in VS Code
- Show only what they need
- Pair with student who understands

---

## Differentiation Strategies

### For Beginners (Need Extra Support)
- **Pre-written template:** Give them template file to start
- **Step-by-step:** Break instructions into smaller steps
- **Pair programming:** Pair with intermediate student
- **Visual aids:** Show pictures/diagrams
- **One-on-one:** Give extra attention during practice
- **Simpler text editor:** Use basic Notepad/TextEdit

**Modifications:**
- Start with just `<h1>` and `<p>` tags
- Add other tags later
- Focus on completion, not perfection

### For Intermediate Students (Ready for More)
- **Challenge:** Add more HTML tags (`<strong>`, `<em>`, `<br>`)
- **Challenge:** Create multiple pages and link them
- **Challenge:** Add an image
- **Mentor role:** Help other students
- **Advanced:** Introduce basic CSS inline styles

**Extensions:**
- Learn about semantic HTML (`<header>`, `<footer>`, `<nav>`)
- Explore more link types (email, phone)
- Research HTML5 features

### For Advanced Students (Can Move Faster)
- **Project:** Build a multi-page website
- **Teaching:** Help explain concepts to others
- **Exploration:** Research HTML attributes
- **Next steps:** Preview CSS styling

**Advanced Topics:**
- HTML attributes (`id`, `class`)
- Semantic HTML elements
- HTML validation
- Accessibility basics

### For Students Uncomfortable with English
- **Visual demonstration:** Show, don't just tell
- **Translation:** Use Google Translate for key terms
- **Pair with translator:** Partner with bilingual student
- **Simplified language:** Use simple words
- **Check understanding:** Ask yes/no questions

---

## Assessment Checkpoints

### After Part 3 (Creating HTML File)
**Check:**
- [ ] Can students create an HTML file?
- [ ] Do they understand basic HTML structure?
- [ ] Can they identify opening/closing tags?

**If not:** Review structure, show example again

### After Part 4 (Viewing Website)
**Check:**
- [ ] Can students open their webpage in browser?
- [ ] Do they understand saving and refreshing?
- [ ] Are they excited about their creation?

**If not:** Help troubleshoot, celebrate small wins

### After Part 5 (Adding Content)
**Check:**
- [ ] Can students add headings, lists, links?
- [ ] Do they understand different tag purposes?
- [ ] Are they comfortable experimenting?

**If not:** Review tags, provide more examples

### Final Checkpoint
**Students should be able to:**
- [ ] Create an HTML file from scratch
- [ ] Use at least 5 different HTML tags
- [ ] View their webpage in a browser
- [ ] Make changes and see updates

**If struggling:** Provide template, extra help, or pair with mentor

---

## Wrap-Up & Next Steps

### Recap (2 minutes)
**Key Points to Emphasize:**
- "HTML is the structure of websites"
- "Every tag has a purpose"
- "Save, then refresh browser to see changes"
- "You can experiment - if it breaks, we fix it!"

### Homework/Follow-Up (Optional)
- **Practice:** Add 3 more things to your webpage
- **Challenge:** Add an image of Koh Phangan
- **Explore:** Look at other websites - right-click → "View Page Source"

### Next Workshop Preview
- "Next time: Making it beautiful with colors and fonts!"
- "We'll learn CSS - the styling language"
- "Bring your webpage from today!"

### Resources to Share
- Student workshop guide: `workshops/workshop-1-hello-world.md`
- Template file: `templates/hello-world-template.html`
- Online resources: MDN Web Docs, W3Schools

### Contact for Questions
- Email: guillaume@islandcodeforlocals.com
- WhatsApp group: [if available]

---

## Additional Notes

### Timing Adjustments
- **If running short:** Add more practice time, introduce more tags
- **If running long:** Skip optional challenges, focus on basics

### Cultural Considerations
- Encourage students to write in their language
- Celebrate local businesses they mention
- Make connections to Koh Phangan community

### Energy Management
- Keep energy high with enthusiasm
- Take breaks if needed
- Celebrate small wins often
- End on positive note

### For Next Time
- Note what worked well
- Note what was confusing
- Adjust pacing for next workshop
- Prepare for CSS introduction

---

**Remember:** This is their first website! Make it fun, encouraging, and celebrate their success! 🎉

