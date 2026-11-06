# Lab 3 – Responsive Portfolio Website

## Description
A one-page responsive portfolio website built with HTML and CSS, enhancing the Lab 2 project with modern layout and animation techniques.

**Sections:** Header, Hero, About, Skills, Projects, Contact, Footer

**CSS techniques used**
- **Flexbox** – header (logo + nav), hero (text left, image right), footer, contact form
- **CSS Grid** – Skills and Projects cards (4 / 3 / 2 / 1 columns depending on screen size)
- **Media queries** – mobile-first design with `min-width` breakpoints
- **Relative units** – `rem`, `em`, `%`, `vw`, `vh` instead of fixed pixels
- **Transitions & transforms** – hover effects on nav links, buttons, cards and footer links
- **Keyframe animations** – color-changing "Full Stack Developer" text, hero slide-in, floating profile image, scroll fade-in for sections
- **Typography** – Google Font *Poppins* with a clear heading / subheading / body hierarchy
- **Color theme** – dark navy (background), teal (primary), purple (secondary)

## Files
| File | Purpose |
|------|---------|
| `index.html` | Page structure and content |
| `style.css` | All styling, animations and media queries |
| `README.md` | Project documentation |

## How to View the Responsive Behavior
1. Open `index.html` in a browser (Chrome / Edge / Firefox).
2. Press **F12** to open DevTools, then click the **device toolbar** icon (or press **Ctrl + Shift + M**).
3. Resize the viewport or choose a device preset and check the layouts below.

### Breakpoints tested
| Screen | Width | Layout |
|--------|-------|--------|
| Mobile | below 768px (48em) | Hero text above image, all cards in 1 column, header stacked |
| Tablet | 768px – 1023px (48em – 64em) | Header in one row, cards in 2 columns |
| Desktop | 1024px and above (64em+) | Hero text left and image right, Skills in 4 columns, Projects in 3 columns |

Also tested on: Chrome, Edge, Firefox.

## Customization
- Replace the placeholder image in the hero section with your photo (`src="profile.jpg"`).
- Update the About, Skills and Project details and links.

## Author
Vaibhav Chaudhary – CSE (AI & ML) Student
