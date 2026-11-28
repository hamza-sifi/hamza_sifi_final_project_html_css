# Break the Silence

Hey! 👋 This is a project I built to talk about gender-based violence (GBV) in Morocco. The idea is simple: give survivors, witnesses, and allies one place to find information, know their rights, and most importantly — find real help.

I built it for the **16 Days of Activism Against Gender-Based Violence** campaign (November 25 to December 10).

---

# What is this project?

It's a multi-page website. Basically, here's what people can do on it:

- Understand the different types of violence (physical, psychological, sexual, digital, domestic)
- Learn about survivors' rights and how to access justice
- Find support organizations and emergency numbers
- Report an incident through a confidential form
- Follow the campaign timeline and read some articles

I chose warm colors (reds, oranges, and creams) because I wanted the site to feel safe and hopeful, not cold or scary. It's also responsive, so it works well on phones and computers.

---

 #How the project is organized

├─ index.html # Homepage
├── public/
│ ├── css/
│ │ ├── output.css # Compiled Tailwind CSS
│ │ └── index.css # My custom CSS for the contact page
│ ├── images/ # Logos, backgrounds, article images, org logos
│ └── pages/
│ ├── campaign.html # The campaign in detail
│ ├── contact.html # The confidential form
│ └── Help.html # Resources and emergency numbers


### The pages

| Page | What's on it |
|------|---------|
| **index.html** | Homepage: campaign intro, types of violence, latest articles |
| **campaign.html** | Why justice matters, rights, the 4-step journey, 16 Days timeline |
| **Help.html** | Legal rights, support orgs, emergency numbers, authority contacts |
| **contact.html** | Confidential form to report (name, email, violence type, details) |

---

##  What I used

### The basics
- **HTML5** — I made sure to use semantic tags on every page
- **CSS3** — For custom styling on the contact page

### The framework
- **Tailwind CSS** — This does most of the styling:
  - Custom colors (`#860613`, `#e27646`, `#faf0d9`, etc.)
  - Responsive breakpoints (`max-sm:` for mobile)
  - Flexbox and grid
  - Hover states and transitions
  - Font weights and spacing

### The icons
- **Bootstrap Icons** — SVGs (shield, calendar, phone, hand, laptop, etc.)
- **Tabler Icons** — Extra icons (heart-handshake, scale, gavel, calendar)

### Interactivity (no JavaScript!)
- **CSS-only mobile menu** — I used a hidden checkbox (`peer`) to open and close the mobile menu with pure CSS (`peer-checked:right-15`). No JS needed.

### Design
- Responsive on mobile, tablet, and desktop
- Rounded navigation and cards (pill style)
- Background images with `bg-cover` and `bg-center`
- Hover shadow effects on cards and buttons

> **Note:** This project uses **no JavaScript** — even the mobile menu is done with Tailwind.


##  Features

-  Fully responsive (mobile, desktop)
-  Same navigation and footer on every page
-  CSS-only hamburger menu
-  Good color contrast and semantic HTML
-  Emergency numbers clearly visible (1325, 17, 177, 112)
-  Confidential reporting form with violence-type selector
-  Structure ready for translations (English content, Moroccan context)


Color palette
Color-------Hex----------	Where I used it
DeepRed #860613-------	Headings, main brand color
Crimson #910a1a------	CTA buttons
Burnt Orange	#e27646 -----------	Accents, secondary buttons
Warm Peach	#ffd8b9 ---------	Navbar background
Cream	#faf0d9 ----------	Header background
Soft Beige	#fdf3e8 ------	Section backgrounds
Light Peach	#f6ba96 ----------	Card backgrounds
Golden  Orange	#f69120 -------	Footer

