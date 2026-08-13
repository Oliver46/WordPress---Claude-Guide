Create A Website With WordPress And Claude Prompting Guide
---------------------------------------------------------------------------------------------

- Appearance -> Theme -> Install -> Install Astra Theme
- Go to plugin -> add plugin
- Install Elementor Website Builder by Elementor
- Install WPForms by Syed Balkhi
- Install XPRO theme builder for Elementor - free by XPRO
- Install XPRO Elementor Addons

***** The XPRO plugin allows us to BUILD a CUSTOM HEADER and FOOTER with Elementor *****

- Install novamira.ai
***** It will connect with Claude. It connects them together and imports the website.
       novamira.ai teaches the AI about Elementor to make sure we have a smooth transition. *****

- Download the file (novamira.ai). Then, add it as plugin.
- Adjust the Elementor options.
- Go to Elementor settings ->  Disable the Atomic Editor
- Click on Deactivate
- Go to Features -> Scroll down -> Container
- Select Active on container.
- Then save changes 

***** By selecting the container, we are going to force Claude to tuse Flexbox and not the intersections.******







Guide To Create The Website With Claude
---------------------------------------------------------------------------------------------
Design a complete 5-page website for my business using HTML. Make it look modern, clean, and professional. give it unique designs and make sure the design beats my competitors

Business name: [YOUR BUSINESS]
What I do: [YOUR SERVICES]
Who I serve:[CUSTOMERS YOU SERVE]
Main goal of the site: [GET LEADS / BOOK CALLS / SHOWCASE WORK]
SEO keywords: [KEYWORD 1. KEYWORD 2, KEYWORD 3]

Build these 5 pages:
<br>
Home — Hero with headline + CTA, trust strip, 3 key benefits, services preview, testimonials, about preview, final CTA
<br>
About — Story, mission, what makes me different, CTA
<br>
Services — Service grid with descriptions, how-it-works steps, FAQ, CTA
<br>
Listings (portfolio/products/properties) — Card grid with Unsplash images, filter bar, CTAs
<br>
Contact — Form (Name, Email, Phone, Message), contact info, map, social links
<br>
Header: Sticky, logo + nav (Home, About, Services, Listings, Contact) + Contact CTA button + mobile menu
Footer: Logo, quick links, contact info, socials, copyright
Requirements:
Modern, clean design — you pick the colors, fonts, and style that fit my business best
Fully mobile responsive
All links and buttons work
Unsplash images that fit my niche
SEO-ready (meta titles, H1s, alt text, semantic HTML) Build it as one artifact I can preview and export.

--------------------------------------------------------------------------------------------------
Guide To Import The Website (Claude  Desktop ONLY)

Create a new Menu for pages created for this design. Make sure to also set the home page. 

I want you to take this design and convert it for the elementor page builder for wordpress. Make sure to use the native elementor elements and not HTML widgets. Use the container and not inner sections. Also i have disabled the atmoic editor, do not use the atmoic elements. We have installed novamira plugin to help you understand how to use elementor elements better

****If you have Elementor pro installed already, do not use the prompt about XPRO plugin - use this prompt - I want you to use the elementor PRO version to create a custom header and footer using the theme builder. Make you to save the header and footer template in the library so i can customize them later, Also create a mega menu with blurbs and video, make the mega menu use the elementor elements and stand out. Also create a popup for users who want to register  - but just store it in the library and i will apply it later.****

Next Use XPRO to design the create the header and footer. This plugin allows you to build a custom header and footer with elementor. Do not use the Elementor pro widgets, use the elements provided by XPRO Make sure to save the header and footer template in the XPRO library so i can customize them later.

Use WPforms as the contact form for the contact page.

can you now convert this website and push it to my domain connect https://pattywacktutorial.com

links: 
youtube: https://www.youtube.com/watch?v=El484PgSHEk&t=1710s
---------------------------------------------------
Guide: https://tiberium.app/p/3uTL2aV1aoV9
---------------------------------------------------
Website: https://www.leonoliver.com/claude1/
---------------------------------------------------
file:///Users/oliverleon/Downloads/oliver-estate_5.html

---------------------------------------------------------------------------------------------

PROMPT (SCREENSHOT VERSION):
----------------------------
I'm attaching a screenshot for design inspiration. Build me a complete 6-page website in HTML and CSS based on the style, layout, and vibe of this screenshot — but make it BETTER. I want a unique, modern design that stands out from my competitors. 
No JavaScript. No flashy animations. Just clean, modern, well-designed pages.
I have my own design system, so put CSS variables at the top of the stylesheet for colors, fonts, spacing, and border-radius — I'll swap in my own values after.

MY BUSINESS INFO — use this to generate all content (headlines, copy, services, blog titles, meta descriptions, etc.):
MY BUSINESS INFO — use this to generate all content AND inform the design direction:
Business name: [ENTER BUSINESS NAME]<br>
What you do / services offered: [LIST SERVICES]
Who you serve (target audience): [DESCRIBE IDEAL CUSTOMER — be specific]<br>
Location (if local): [CITY/AREA OR LEAVE BLANK]<br>
SEO keywords to target: [LIST 5-10 KEYWORDS]<br>
Brand tone: [PROFESSIONAL / FRIENDLY / BOLD / LUXURY / PLAYFUL / MINIMALIST]<br>
Primary CTA (what you want visitors to do): [E.G., BOOK A FREE CALL, GET A QUOTE, SUBSCRIBE]<br>
Contact info: [EMAIL, PHONE, SOCIAL LINKS — OR LEAVE BLANK FOR PLACEHOLDERS]<br>
Write all copy directly to the target audience, weave keywords in naturally (no stuffing), and match the brand tone. Headlines should be benefit-focused, not generic.<br>
Pages to create (all linked in the navigation and footer):<br>
Home
About
Services
Portfolio
Contact
Requirements:
Separate HTML file per page (index.html, about.html, services.html, portfolio.html, blog.html, contact.html) with one shared styles.css.<br>
All links use relative paths so the site works locally when opened by double-clicking index.html.<br>
Mobile-first responsive design — perfect on phone, tablet, and desktop.<br>
SEO optimized — unique meta tags per page (title, description, Open Graph, Twitter cards) using the business info and keywords, semantic HTML5 tags, schema.org JSON-LD (Local Business or Organization) in the <head>.<br>
Images: use https://source.unsplash.com/[width]x[height]/?[keyword] for all photos — pick keywords that match the business and section context (e.g., "workspace", "team", "interior"). Every image needs descriptive alt text and loading="lazy".<br>
No external libraries, no frameworks, no icon packs. Use inline SVG for icons.<br>
Include a favicon link in the <head> (use an emoji favicon via SVG data URI so I don't need an external file).<br>
Design direction:<br>
Modern layouts — grid-based sections, strong visual hierarchy, thoughtful whitespace, asymmetric layouts where it fits. Subtle hover states are fine.<br>
Each page should feel distinct, not the same template recycled 6 times.<br>
Include at least 2 unique section types most competitor sites DON'T have — pick from: process timeline, comparison table, FAQ accordion (CSS-only using <details> and <summary>), pricing tiers, stats/results section, testimonial grid, or before/after layout.<br>
Footer with copyright year, quick links, social icons (inline SVG), and contact info.
Forms and accessibility:<br>
Contact form — pure HTML with required attributes and HTML5 input types for built-in validation.<br>
WCAG AA accessible, keyboard navigable, proper focus states styled in CSS.<br>
Build all 6 pages and the stylesheet in full. No placeholders for content, no "add content here" shortcuts, no truncation. Make it production-ready.



