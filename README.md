# laravel-angular.io

Static archive of laravel-angular.io. There is no build step: `public/` is exactly what gets deployed.

- **Edit**: change the HTML in `public/` directly. The "archived" course list is repeated in every page, so use find-and-replace across `public/` (e.g. search for `Learn HTML CSS`).
- **Preview**: `npm start`, then open http://localhost:8080
- **Deploy**: commit, then `npm run deploy` (pushes `public/` to the `gh-pages` branch).
