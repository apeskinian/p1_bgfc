# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | Link | Screenshot |
| --- | --- | --- | --- |
|  | index.html | [Validate index.html](https://validator.w3.org/nu/?doc=https://apeskinian.github.io/p1_bgfc/index.html) | ![screenshot](documentation/validation/validate-html-index.png) |
|  | upcoming.html | [Validate upcoming.html](https://validator.w3.org/nu/?doc=https://apeskinian.github.io/p1_bgfc/upcoming.html) | ![screenshot](documentation/validation/validate-html-upcoming.png) |
|  | newsletter.html | [Validate newsletter.html](https://validator.w3.org/nu/?doc=https://apeskinian.github.io/p1_bgfc/newsletter.html) | ![screenshot](documentation/validation/validate-html-newsletter.png) |
|  | confirmation.html | [Validate confirmation.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fapeskinian.github.io%2Fp1_bgfc%2Fconfirmation.html) | ![screenshot](documentation/validation/validate-html-confirmation.png) |
|  | 404.html | [Validate 404.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fapeskinian.github.io%2Fp1_bgfc%2F404.html) | ![screenshot](documentation/validation/validate-html-404.png) |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | Link | Screenshot |
| --- | --- | --- | --- |
| assets | style.css | [Validate style.css](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fapeskinian.github.io%2Fp1_bgfc) | ![screenshot](documentation/validation/validate-css.png) |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Upcoming Events | Newsletter | Confirmation | 404 | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browsers/chrome/chrome-index.png) | ![screenshot](documentation/browsers/chrome/chrome-upcoming.png) | ![screenshot](documentation/browsers/chrome/chrome-newsletter.png) | ![screenshot](documentation/browsers/chrome/chrome-confirmation.png) | ![screenshot](documentation/browsers/chrome/chrome-404.png) | Works as expected |
| Firefox | ![screenshot](documentation/browsers/firefox/firefox-index.png) | ![screenshot](documentation/browsers/firefox/firefox-upcoming.png) | ![screenshot](documentation/browsers/firefox/firefox-newsletter.png) | ![screenshot](documentation/browsers/firefox/firefox-confirmation.png) | ![screenshot](documentation/browsers/firefox/firefox-404.png) | Works as expected |
| Edge | ![screenshot](documentation/browsers/edge/edge-index.png) | ![screenshot](documentation/browsers/edge/edge-upcoming.png) | ![screenshot](documentation/browsers/edge/edge-newsletter.png) | ![screenshot](documentation/browsers/edge/edge-confirmation.png) | ![screenshot](documentation/browsers/edge/edge-404.png) | Works as expected |
| Safari | ![screenshot](documentation/browsers/safari/safari-index.png) | ![screenshot](documentation/browsers/safari/safari-upcoming.png) | ![screenshot](documentation/browsers/safari/safari-newsletter.png) | ![screenshot](documentation/browsers/safari/safari-confirmation.png) | ![screenshot](documentation/browsers/safari/safari-404.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Upcoming | Newsletter | Confirmation | 404 | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsive/mobile-devtools-index.png) | ![screenshot](documentation/responsive/mobile-devtools-upcoming.html.png) | ![screenshot](documentation/responsive/mobile-devtools-newsletter.png) | ![screenshot](documentation/responsive/mobile-devtools-confirmation.png) | ![screenshot](documentation/responsive/mobile-devtools-404.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsive/tablet-devtools-index.png) | ![screenshot](documentation/responsive/tablet-devtools-upcoming.html.png) | ![screenshot](documentation/responsive/tablet-devtools-newsletter.png) | ![screenshot](documentation/responsive/tablet-devtools-confirmation.png) | ![screenshot](documentation/responsive/tablet-devtools-404.png) | Works as expected |
| 4k Monitor (DevTools) | ![screenshot](documentation/responsive/4k-devtools-index.png) | ![screenshot](documentation/responsive/4k-devtools-upcoming.png) | ![screenshot](documentation/responsive/4k-devtools-newsletter.png) | ![screenshot](documentation/responsive/4k-devtools-confirmation.png) | ![screenshot](documentation/responsive/4k-devtools-404.png) | Scaling issues beginning |
| iPhone 15 Pro | ![screenshot](documentation/responsive/mobile-iphone15pro-index.PNG) | ![screenshot](documentation/responsive/mobile-iphone15pro-upcoming.PNG) | ![screenshot](documentation/responsive/mobile-iphone15pro-newsletter.PNG) | ![screenshot](documentation/responsive/mobile-iphone15pro-confirmation.PNG) | ![screenshot](documentation/responsive/mobile-iphone15pro-404.PNG) | Works as expected |
| iPad Mini | ![screenshot](documentation/responsive/mobile-ipadmini-index.PNG) | ![screenshot](documentation/responsive/mobile-ipadmini-upcoming.PNG) | ![screenshot](documentation/responsive/mobile-ipadmini-newsletter.PNG) | ![screenshot](documentation/responsive/mobile-ipadmini-confirmation.png) | ![screenshot](documentation/responsive/mobile-ipadmini-404.PNG) | Works as expected |
| MacBook Air M3 | ![screenshot](documentation/responsive/laptop-macbookairm3-index.png) | ![screenshot](documentation/responsive/laptop-macbookairm3-upcoming.png) | ![screenshot](documentation/responsive/laptop-macbookairm3-newsletter.png) | ![screenshot](documentation/responsive/laptop-macbookairm3-confirmation.png) | ![screenshot](documentation/responsive/laptop-macbookairm3-404.png) | Works as expected |
| 2K Desktop Monitor | ![screenshot](documentation/responsive/desktop-1440p-index.png) | ![screenshot](documentation/responsive/desktop-1440p-upcoming.png) | ![screenshot](documentation/responsive/desktop-1440p-newsletter.png) | ![screenshot](documentation/responsive/desktop-1440p-confirmation.png) | ![screenshot](documentation/responsive/desktop-1440p-404.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/lighthouse-mobile-index.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-index.png) | Font Awesome and Google Fonts highlighted as render blocking resources on mobile |
| Upcoming | ![screenshot](documentation/lighthouse/lighthouse-mobile-upcoming.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-upcoming.png) | Some minor warnings |
| Newsletter | ![screenshot](documentation/lighthouse/lighthouse-mobile-newsletter.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-newsletter.png) | Some minor warnings |
| Confirmation | ![screenshot](documentation/lighthouse/lighthouse-mobile-confirmation.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-confirmation.png) | Accessibility lowered due to automatic refresh meta tag, also Font Awesome and Google Fonts highlighted as render blocking resources on mobile |
| 404 | ![screenshot](documentation/lighthouse/lighthouse-mobile-404.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-404.png) | Font Awesome and Google Fonts highlighted as render blocking resources on mobile |

## User Story Testing

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to learn about what happens at the club, so that I can decide whether I would like to try it. | ![screenshot](documentation/screenshots/bgfc-what-who-where.png) |
| As a new site user, I would like to find out where the club meets, so that I can see if it's local enough for me. | ![screenshot](documentation/screenshots/bgfc-map.png) |
| As a new site user, I would like to learn when the next meetup is, so that I can see if I can attend that time. | ![screenshot](documentation/screenshots/bgfc-upcoming-page.png) |
| As a returning site user, I would like to be kept up to date with events, so that I can see what's happening at the next meet. | ![screenshot](documentation/screenshots/bgfc-upcoming-page.png) |
| As a returning site user, I would like to know about past events I may have missed, so that I can catch up on what happened and who won the last tournament. | ![screenshot](documentation/screenshots/bgfc-newsletter-page.png) |

## Bugs

- A screenshot for the README.md was named bgfc-title&hero.png so was changed to bgfc-title-hero.png to remedy any issues that would have been caused.

> [!NOTE]  
> There are no remaining bugs that I am aware of.
