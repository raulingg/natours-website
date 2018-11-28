# Natours website

> created in order to learn advanced concepts about `css` and `sass`.

The website was based on `Natours` landing page design and implemented from scratch following the best practices covered during the "Advanced CSS and SASS" course by [Jonas Schmedtmann](https://codingheroes.io/), practicec like [BEM](http://getbem.com/) , [7-1 architecture pattern](https://sass-guidelin.es/#the-7-1-pattern) and responsive design.

## Installing

run the following command

with yarn

```sh
yarn
```

with npm

```sh
npm install
```

## Development

run the following command in dev environment

with yarn

```sh
yarn start
```

with npm

```sh
npm run start
```

## Building for production

1.  run the following command to generate `style.css` for production environment

    with yarn

    ```sh
    yarn build
    ```

    with npm

    ```sh
    npm run build
    ```

2.  afterward change the following lines into `index.html`

    ```html
    <link rel="stylesheet" href="css/icon-font.css" />
    <link rel="stylesheet" href="css/style.css" />
    ```

    for this only line

    ```html
    <link rel="stylesheet" href="css/build/style.css" />
    ```
