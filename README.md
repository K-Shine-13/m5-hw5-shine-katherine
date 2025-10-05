# m5-hw5-shine-katherine
Auditing for A11y

## AUDIT:
Initial Chrome Lighthouse UI Report:
- Performance = 100
- Accesibility = 93
- Best Practices = 100
- SEO = 90

Initial WAVE Tool Extention Report:
- 3 Errors (Label)
- 12 Contrast Errors
- 2 Alerts

## ALTERATIONS:
- Changed .footer class --> footer semantic tag.
    - Changed text color from #555 --> white for legibility.
    - Also increased font size of footer text from 14px --> 16px.
    - Bolded footer text.
    - Decreased padding to more closely resemble original appearance.
- Changed .nav a color from #333 --> white for legibility.
- Changed body type color from #999 --> #0000 for legibility.
- Created .content h2 CSS style rule.
    - Increased h2 font size to 35px.
    - Set color to black(#0000) for legibility.
- Increased hero.h1 font size.
    - Also changed h1 color to white.
    - Set background in hero.h1 to black to eliminate legibility issue with the background image.
- Added label HTML tags to form-section to eliminate 3 label errors.
    - Created matching label for each section id.
    - Set id for each section form tag to match new labels.
    - Created new CSS rule ".sr-only" to maintain hidden form labels in front-end view but still be readable to screen readers.
