# Taft Highway Church of Christ Website

**ETSU CSCI 1210 Final Project · Group 3 · Best Web Developers Ever**

This five-page website helps first-time visitors plan a visit and gives church members a place to find news and upcoming events. The current version uses static HTML and a shared CSS file.

## Pick a page

Claim a page in the team chat and put your name in the **Owner** column. Start with the existing draft. If you’re waiting on information from the church, put the question in the **Still needed** column so the group can follow up.

| Page                       | Owner     | Still needed                                                                                                                                                                         |
| -------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Home (`index.html`)        | Unclaimed | Add the confirmed worship schedule and approved banner artwork or photo when available. Check the **Plan Your Visit** link.                                                          |
| About (`about.html`)       | Unclaimed | Add the church’s approved history, mission, beliefs, and leadership details. Publish each draft section when its content is ready.                                                   |
| Visit (`visit.html`)       | Unclaimed | Add confirmed worship times, the street address, written directions, a map link, and details about parking, accessibility, and visiting with children.                               |
| Bulletin (`bulletin.html`) | Unclaimed | Add the first approved announcements and upcoming events. Include dates, locations, and confirmed times where applicable. Replace the temporary message once entries are posted.     |
| Contact (`contact.html`)   | Unclaimed | Add verified email and phone links, the street address, and directions. Publish social links, community information, or a prayer request contact method if the church approves them. |

## Coordinate shared work

- **Navigation:** Use **Home · About · Visit · Bulletin · Contact** in both the header and footer. Set `aria-current="page"` on the active page’s links.
- **Church details:** Home and Visit should show the same worship schedule. Use the same verified street address wherever it appears. Let the other page owners know when the church confirms or corrects those details.
- **Shared styles:** All five pages use `css/style.css`. Coordinate changes there with the group because they can affect every page.
- **Design references:** Use Phase 2A for the **Hearth & Evergreen** visual design and Phase 2B for usability and accessibility. The five pages in the table are the current sitemap.
- **Bulletin updates:** Add entries directly in `bulletin.html` for this version. Uploading a bulletin file and updating the page from it is a future enhancement.

## Run the site locally

1. Clone the repository or open your existing copy in GitHub Desktop.
2. Open `index.html` in a browser. Keep the HTML files in the project root and the stylesheet at `css/style.css` so the relative links work.
3. Refresh the browser after saving a change. Use the header and footer links to move between pages.

## Share your changes

1. Create a branch for your page, such as `update-visit`.
2. Commit and push your changes from GitHub Desktop.
3. Open a pull request and ask a teammate to review it. In the description, say what you changed, what you checked, and what still needs confirmation.

### Before requesting review

- [ ] Open the page at desktop and phone widths. Enlarge the text and check that nothing clips or forces horizontal scrolling.
- [ ] Use `Tab` to check the skip link, visible focus, and the order of links and buttons.
- [ ] Check the header, footer, page links, and current-page indicator.
- [ ] Give informative images descriptive alt text and decorative images `alt=""`.
- [ ] Check that published church details are confirmed and draft placeholders are hidden.
