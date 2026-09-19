# Aura Campus Events

## Project Description

Aura Campus Events is a campus event guide for Aura University students. The site helps students discover upcoming activities, learn about event details, and find opportunities to connect with the campus community.

## Layout Decisions

- **Flexbox:** The header uses Flexbox to place the site identity and navigation on opposite sides while allowing the navigation links to wrap. The hero uses Flexbox to center its text over the background image. The related event cards use Flexbox with wrapping so the cards can fit different screen widths.
- **CSS Grid:** The home page uses a 12-column Grid for the upcoming event cards. The featured event page uses Grid to place the main event content beside the event-details sidebar on desktop.

## Responsive Design

The stylesheet uses two breakpoints:

- **850px:** Reduces the event page columns and decreases the hero height.
- **650px:** Changes the header to a vertical layout, left-aligns the navigation, stacks the event sidebar below the main content, and reduces the main heading size.

The pages were tested by resizing the browser window across desktop, medium, and narrow widths to confirm that the navigation wraps, the event sidebar stacks, and the related event cards wrap without overlapping.

## Semantic HTML

- `<header>` identifies the site header and the event introduction header.
- `<nav>` identifies the primary and footer navigation areas.
- `<main>` identifies the primary content of each page. Each page uses exactly one main element.
- `<section>` groups related content, such as upcoming events, the About section, and event information.
- `<article>` represents individual event cards and the featured event.
- `<aside>` contains supporting event details, including the date, location, organizer, and admission information.
- `<time>` provides dates and times for events.
- `<footer>` contains copyright, contact, and footer navigation information.

## Sources

Images: The event images are local files in the `images/` folder: `artfestival.jpg`, `leadershipevent.jpg`, `rechargeevent.jpg`, `lecture.jpg`, `tablingevent.jpg`, and `univpic.jpg`. They are all free stock photos.
Fonts: The site uses the Arial font family.
Content: Event names, descriptions, schedules, and organization details were made up by me
