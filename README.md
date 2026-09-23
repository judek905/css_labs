Project Stylesheets — README

learn.css — The Practice/Learning Stylesheet
This one is basically a learning exercise — a clean, beginner-friendly stylesheet built to understand the fundamentals of styling a website from scratch. Think of it as the "training wheels" version: simple, well-commented, and easy to follow line by line.

What it covers:

A basic CSS reset (removing default browser margins/padding so nothing looks weird by default)
Simple typography and body styling using a light, neutral color palette
A sticky header with a horizontal navbar
A centered hero section with a heading, paragraph, and call-to-action button
A reusable .btn class for buttons
A responsive card/grid layout — handy for things like product listings or blog previews
A basic footer
Media queries at the bottom so the layout adjusts nicely on tablets and phones
Color style: light background, soft grays, and a warm brown/orange accent color (
#b5651d). Friendly, approachable, general-purpose.

Best used for: practicing core CSS concepts, or as a starting template for a simple, everyday website (portfolio, blog, small business site, etc.) — nothing fancy, just solid fundamentals.

style.css — The Luxury Brand Stylesheet
This one is a step up — it's a premium, high-end design system meant for a company that wants to look sophisticated, expensive, and elegant. Think fashion houses, five-star hotels, private jewelers, or boutique consulting firms — that kind of vibe.

What makes it "luxurious":

A deep black background with a warm gold accent color — a classic high-end color combo
Elegant serif headings (Playfair Display) paired with a clean modern sans-serif body font (Jost)
Lots of breathing room — generous padding and spacing so nothing feels cramped or cheap
Slow, smooth transitions (0.5s) instead of snappy ones — luxury brands move unhurriedly, and the animations reflect that
A full-screen cinematic hero section with a background image and dark overlay
Minimal, outlined buttons with a gold "fill-in" hover effect
A fixed navbar that starts transparent and turns solid once you scroll (a common technique on luxury sites)
An editorial-style image gallery with a subtle zoom effect on hover
A dedicated testimonials section styled like a quote from a magazine
A clean contact form with minimal underlined inputs (no boxy borders — feels more refined)
Everything is built using CSS variables (:root) at the top, so the whole color palette, fonts, and spacing can be swapped out in one place without hunting through the whole file
Color style: near-black (
#0a0a0a), gold (
#c9a24b), and cream (
#f5f1e8) — a rich, moody, upscale palette.

Best used for: a real luxury or premium brand website — something that needs to feel exclusive and high-quality at first glance.

Quick Comparison
learn.css	style.css
Purpose	Learning fundamentals	Premium brand design
Mood	Friendly, simple	Elegant, exclusive
Colors	Light background, warm brown accent	Black background, gold accent
Fonts	System font stack	Playfair Display + Jost (Google Fonts)
Animations	Quick (0.3s)	Slow and deliberate (0.5s)
Best for	Everyday websites, practice projects	High-end company/brand websites
 
  How to Use Either File
Save the CSS file in your project folder (e.g. /css/style.css).
Link it inside your HTML <head>:
html
   <link rel="stylesheet" href="style.css">
Make sure your HTML class names match the ones used in the CSS (.navbar, .hero, .btn, .card, .gallery, etc.) so the styles actually apply.
For style.css, don't forget to swap in your own hero background image where it says url('hero-image.jpg').
That's it! If you want, this README can be expanded later with setup instructions, folder structure, or deployment notes once the rest of the site comes together.


