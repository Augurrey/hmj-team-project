[🇺🇦 Українська](README.uk.md)

# Handmade Jewelry

## Project name

**Handmade Jewelry** is a team project from the **HTML + CSS** module.

## About the project

The project was completed as part of the **FullStack Developer** course at [GoIT Academy](https://goit.global/ua/).

It is based on the [Vanilla App Template](https://github.com/goitacademy/vanilla-app-template).

### Links

- [Website design](https://www.figma.com/design/54aZckZU4SZP8BtBARsYVU/Handmade-Jevelery?node-id=8202-62143&t=bU2eq9SkkgnQUH7v-0)
- [Technical specification](https://docs.google.com/spreadsheets/d/16rx-hTSMhKpxae0-HjRQJNME0Lq8PWhv-zKCYqE2bVk/edit?gid=0#gid=0)
- [Trello board](https://trello.com/invite/b/69f26ae71778845fcaadf2b9/ATTI072e4cae23896f19e574cf8bc04b7f4bD67A3F48/hmj-team-project)

## Project workflow

The implementation was divided into ten areas:

1. Header
2. Hero section
3. About section
4. Benefits section
5. Gallery section
6. Testimonials section
7. Contacts section
8. Footer
9. Mobile menu
10. Additional tasks

Each core area, except the last two, was divided into four tasks:

1. HTML - preparing the section markup
2. Mobile CSS - implementing the mobile layout
3. Tablet CSS - implementing the tablet layout
4. Desktop CSS - implementing the desktop layout

The team worked on sections in parallel and completed tasks within each section sequentially. Contributors selected tasks from the To Do list.

## Team

- **Yurii Boiko** - Team Lead  
  Repository setup, header HTML, testimonials tablet CSS, code review, bug fixing, and refinements for the gallery, testimonials, and footer CSS.
- **Ihor Hulchak** - Web Developer  
  Hero mobile CSS, About HTML and desktop CSS, Testimonials HTML, Contacts HTML and mobile/desktop CSS, bug fixing, and additional tasks.
- **Iryna Antoniuk** - Web Developer  
  About mobile CSS, footer HTML and mobile/desktop CSS, mobile menu CSS.
- **Iryna Kukhareva** - Web Developer  
  Benefits mobile/tablet/desktop CSS, contacts tablet CSS, mobile menu HTML.
- **Karyna Bobrovska** - Web Developer  
  Gallery HTML and mobile/tablet/desktop CSS.
- **Tetiana Bondarenko** - Web Developer  
  About tablet CSS, Benefits HTML, testimonials mobile and desktop CSS.
- **Petro Rudyk** - Web Developer  
  Header mobile, tablet, and desktop CSS.
- **Anastasiia Dyshliuk** - Web Developer  
  Hero tablet and mobile CSS.
- **Vladyslav Buhaenko** - Web Developer  
  Hero HTML.

## Technologies

- **HTML5** - page markup
- **CSS3** - responsive layouts
- **Vite** - project bundling
- **JavaScript**

## Project structure

- `src/index.html` - the main page
- `src/partials/` - HTML partials for the header, sections, footer, and more
- `src/css/` - global and section styles
- `src/js/` - JavaScript logic

## Run locally

### Prerequisites

- **Node.js** (LTS recommended)
- **npm** (included with Node.js)

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

Open the address shown by Vite in your browser, usually `http://localhost:5173`.

## Deployment

The project is configured to build with Vite and can be deployed to **GitHub Pages**.

For GitHub Pages, the `package.json` build script includes the base path:

```json
"build": "vite build --base=/hmj-team-project/"
```
