Navbar
  Sections: Home, Services, About Us, Contact Us, built as an unordered list.
  Logo on the left, Username on the right.
  Layout uses only display: inline / display: inline-block (on .logo, .nav-links, .username, and .nav-links li) — no flexbox anywhere in the navbar. Centering is done with line-height (for vertical centering) and percentage width + text-align (for horizontal placement).


Hero Section
  Two divs inside .hero: .hero-left and .hero-right, both display: inline-block so they sit side by side without flex.
  Left div: heading, description, and a "Book a service today!" button, styled to match the sample screenshot (blue accent color, rounded button).
  Right div: an original SVG illustration of a washing machine + laundry basket (assets/washing-machine.svg) — drawn from scratch so there's no copyright/licensing concern with pulling a random image off the internet.
  The whole .hero section is sized with viewport units (100vw wide, calc(100vh - 70px) tall, i.e. the full viewport height minus the navbar) with overflow: hidden, so it always fits the screen exactly and never scrolls, regardless of window size.
