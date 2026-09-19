# Review

## Summary
- Fixed a CSS formatting issue caused by an accidental URL string in the navbar styles.
- Fixed "預訂行程" button scrolling to the booking form (`.booking-box`) instead of the unrelated contact footer.
- Made the three "查看" buttons on destination cards functional — they now scroll to the packages section.
- Set a `min` date on the departure date field so past dates can't be selected.
- Extended dark-mode styles to cover the destinations section background and price tags, which previously stayed light-themed.

## Validation
- Checked the HTML and CSS structure after the fix.
- The accidental injected URL was removed from the `.navbar` block.
- Manually traced each new event listener and confirmed target element IDs/selectors exist.
- No additional syntax issues were detected in the edited sections.

## Status
- Ready for review.

---

## Update: footer text change
- Updated footer tagline text (content-only change, no logic/structure affected).
- Reviewed: no functional or security impact.
- Status: PASS.
