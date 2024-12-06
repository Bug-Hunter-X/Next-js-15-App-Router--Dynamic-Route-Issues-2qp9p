# Next.js 15 App Router Dynamic Route Bug

This repository demonstrates a bug encountered when using dynamic routes in the Next.js 15 App Router.  Routes defined within the `app` directory exhibit unexpected behavior, failing to render correctly with dynamic segments.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe that navigating to dynamic routes does not work correctly.

## Expected Behavior

Dynamic routes should render correctly, passing dynamic segments as props to the page component.

## Actual Behavior

The dynamic routes fail to render, and instead show a 404 error or an unexpected page.

## Additional Context

This bug has been reported and investigated in the Next.js community forums. The solution provided demonstrates a workaround to resolve the issue.