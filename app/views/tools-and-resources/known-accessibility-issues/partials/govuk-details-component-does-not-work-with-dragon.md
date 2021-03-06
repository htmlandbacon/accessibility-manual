## GOV.UK Details component does not work with Dragon

When using Dragon, the GOV.UK Details component will not work with any of the link commands. The Details component has been styled to look like a link but it behaves like a button.

This is a potential failure of [WCAG 4.1.2 - Name, Role, Value](https://www.w3.org/WAI/WCAG21/quickref/#name-role-value), although it has not been flagged as one. The reason it might be a failure is that it looks like a link but cannot be programmatically determined to be one.

It recommended that you do not use the details component. Aside from the potential accessibility failure, research shows that users often miss the information they hide as they don't understand how the component works.

Only have content on the page which your users need. If you have to hide content, then decide if it's really needed or if the page can be broken into multiple pages.

You can read more about this:  
[Github comment about Details component being a potential WCAG fail](https://github.com/alphagov/govuk-design-system-backlog/issues/44#issuecomment-702830874)
