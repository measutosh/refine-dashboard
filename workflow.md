## Things used in this project

- refine framework
- google cloud auth
- MERN stack

## Setup

- npm create refine-app@latest client

- choosen options

```bash
Choose a project template · refine-react
✔ What would you like to name your project?: · client
✔ Choose your backend service to connect: · data-provider-custom-json-rest

✔ Do you want to use a UI Framework?: · mui
✔ Do you want to add example pages?: · inferencer
✔ Do you want to add dark mode support?: · mui-dark-mode
✔ Do you want to customize the Material UI theme?: · mui-extend-theme
✔ Do you want to customize the Material UI layout?: · mui-custom-layout
✔ Do you need any Authentication logic?: · auth-provider-google
✔ Do you need i18n (Internationalization) support?: · no
✔ Do you want to add kbar command interface support?: · no
✔ Choose a package manager: · npm
✔ Would you mind sending us your choices so that we can improve superplate? · yes

```

-npm install apexcharts react-apexcharts

### Login
- add the assets including logo
- in index.html add cdn links to google fonts
- create src/index.css file
- create src/constants/index.ts file
- remove the defaultsrc/interfaces folder content and add fresh ones
- add components/charts
- setup google cloud auth
    - oauth consent screen
    - credentials -> oauth client id
        - authrized js origins
        - authorized redirects 
- add API creds to env file and use it in login.tsx
- LOOK AND FEEL OF LOGIN
    - change the bgcolor
    - add the imported logo

### Sider
- modify components/sider/index.tsx
    - modify the hover effect on sidebars
    - listitemicon, listittext, logout button, drawer, button to expand and collapse the sidebar(color, responsiveness, size)



