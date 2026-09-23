Website files for molinemc.github.io
====================================

Included
  systems.html        the page itself
  img/                14 images: 13 figures plus og-card.png (the link-preview card)
  resume.pdf          current designed resume, which the page links as "Resume (PDF)"

Still needed before publishing
  reports/vercel.pdf
  reports/archive-org.pdf
  paper/asm-acs-2015.pdf
  paper/carpe-spie-2015.pdf
  paper/cat-ijcai-2005.pdf
  paper/goal-based-team-crisis-intervention.pdf
  paper/m-artue-flairs-2013.pdf
  paper/molineaux-dissertation-2017.pdf
  paper/t-artue-flairs-2011.pdf
  (the repo already has a paper/ folder; check which of these are in it)

Publishing notes
  1. The file must be served as systems.html at the repository root.
     The resume prints molinemc.github.io/systems.html, which currently returns 404.
  2. img/ must sit beside it at the root. The link-preview card is referenced by
     absolute URL, https://molinemc.github.io/img/og-card.png, so it will not
     resolve if img/ moves.
  3. Everything else in the page is self-contained: no build step, no external
     CSS or JavaScript, fonts loaded from Google Fonts.
