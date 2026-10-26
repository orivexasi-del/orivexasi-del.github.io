# Nordlys demo shop: the faults on purpose

A static test site for Flinteye. Everything below is intentional; the clean items must NOT be reported.

Faults a good audit should find:
1. Navigation links are tiny tap targets (about 11 px text, 1 px padding).
2. The tagline on the home page is cut off by its box.
3. The product image has no alt text.
4. "In stock, ships tomorrow" is very low contrast.
5. "Add to cart" calls a function that does not exist (page error).
6. "Subscribe" can be submitted many times (no disabling, no guard).
7. The footer link "Careers" leads to a 404.
8. The home page says plans start at 199 kr, the pricing page says Starter costs 249 kr.
9. The company is Nordlys AB in the footer and Nordlys Software AB on About.
10. A price is shown as 248.75000000000003 kr.
11. A German sentence on an English page.

Clean on purpose (must not be reported): a visually hidden "Skip to the main content" text in a 1x1 px box,
the Contact page, the Home link in the footer of Contact.
