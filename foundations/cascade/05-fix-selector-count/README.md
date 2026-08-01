# Fix Selector Count

When two rules use the same **type** of selector (for example, both use only class selectors), the one with **more selectors in that category** wins. Combinators like spaces and `>` do not add any specificity on their own.

Both the HTML and CSS files are filled out for you. Fix the cascade issues by editing the CSS file only. You can add, remove, or edit selectors, or move declaration blocks around. **You should not edit the HTML file or any of the actual style values in the CSS**.

## Desired Outcome

![desired outcome](./desired-outcome.png)

- The text inside `.main` should be **red**.
- The active navigation link should be **orange and bold**.

### Self Check

- Did you make sure to not edit the HTML file?
- Did you increase specificity by adding selectors, not by changing property values?
- Did you avoid changing any property values?
