# CSS Observations

The experiments below describe temporary observations; the original CSS values are restored in the finished page.

1. Changing `.event-planner-container` padding from `20px` to `35px` creates more space between the page edge and its content. The original value is restored.
2. Changing `.events_categories` gap from `30px` to `15px` places the cards closer together. The original value is restored.
3. The Get Started and Send buttons use `#f85199` normally and `#d32b74` while hovered. The `0.3s` transition makes the color change gradual. The original button values are restored.
4. Setting `.events_categories` to `flex-direction: column` stacks the cards vertically. The default Flexbox direction is `row`, which places them side by side. The original row direction is restored for desktop; the mobile media query intentionally uses a column.

## CSS Terms

- **Class selector:** Selects elements by class name. For example, `.events_categories` selects the event category section.
- **Descendant selector:** Selects a matching element nested inside another selector. For example, `.events_categories .event-category h2` selects category headings inside the event section.
- **Padding:** Space inside an element, between its content and its edge. The category list has padding around its items.
- **Margin:** Space outside an element. The sections use top margins to separate them.
- **Flexbox:** A CSS layout system for arranging items in a row or column. The event cards use `display: flex`.
- **`:hover`:** A pseudo-class that applies styles while a pointer is over an element. The buttons use it to change their background color.
