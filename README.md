# Fusion Code - Nidhi Finance Suite (Demo)

## Run in VS Code
1. File > Open Folder > select `nidhi-finance-suite`
2. Install the **Live Server** extension (VS Code will suggest it)
3. Right-click `index.html` > **Open with Live Server**

(You can also just double-click `index.html`.)

## Login
- admin / admin123 (full control)
- staff / staff123 (counter staff)

## Structure
- `index.html` - page shell (login, layout)
- `css/style.css` - theme and UI
- `js/app.js` - all logic: members, loans, deposits, collections, EMI calculator, reports, admin settings, audit log
- `assets/` - Fusion Code logo

## Notes
Data is saved in the browser (localStorage). To make it a real product, replace the `load()` / `save()` functions in `js/app.js` with API calls to a backend (NestJS or ASP.NET Core) and a database.
