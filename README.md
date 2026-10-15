# Apps in the Sky

A home screen of web apps built by Mick and friends. One page, no build step.

## Add an app

Open `index.html` and find the `SECTIONS` list near the bottom. Add a line to the right section, for example:

```js
{ name: "Quiz", by: "Stef", url: "https://example.com/", color: ["#6FA8E0", "#2F5F9E"] },
```

- `name` is the label under the icon. Keep it short.
- `by` is who built it, shown in brackets. Leave it out for Mick's apps.
- `icon` (optional) is a direct link to the app's icon. Without it, the page looks for the usual icon files on the app's site.
- `color` (optional) is two colours for the lettered tile shown when no icon is found.

Apps are sorted A–Z within each section automatically.

## Hosting

GitHub Pages, deploying from the `main` branch, root folder.
