<p align="center">
  <img src="./public/favicon.png" width="150" />
</p>

<p align="center">
  Profile page, but for developers.
</p>

## Screenshots

<p align="center">
  <img src="docs/resources/profile.png" />
</p>

## Acknowledgment

This interface was inspired by the design available on [Dribbble](https://dribbble.com/shots/3508584-Profile-Card-UI).

## Technology stack

This project was developed using cutting edge front-end technologies.

<img src="docs/resources/tech-logos.png" alt="Technologies used">

- [TypeScript](https://github.com/microsoft/TypeScript) — TypeScript is a superset of JavaScript that compiles to clean JavaScript output.
- [Next.js](https://nextjs.org/) — The Next.js is React Based framework with server side rendering capability.
- [Styled Components](https://styled-components.com/) — CSS-in-JS library built for React.
- [React Icons](https://react-icons.github.io/react-icons/) — SVG React icons of popular icon packs using ES6 imports.
- [GitHub GraphQL API](https://docs.github.com/en/rest) — GitHub GraphQL API is used to fetch data from GitHub.
- [DEV REST API]() — DEV REST API is used to fetch data from Dev.to.

## Pre-requisites

Have the following pre-installed:

- [Yarn](https://yarnpkg.com/) — Package manager, similar to [npm](https://www.npmjs.com/)
- [Node](https://nodejs.org/en/)

## Run Locally

Clone the project:

```bash
git clone https://github.com/fariasmateuss/community-user-profile.git
```

Go to the project directory:

```bash
cd community-user-profile
```

Install all dependencies:

```bash
yarn
```

Create a copy of the `.env.example` file called `.env.local`:

```bash
cp .env.example .env.local
```

Add your GitHub App's private key to the `.env.local` file.

> Note: The token is used as the HTTP username.

Start the server:

```bash
yarn dev
```

_or_

```bash
yarn next
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Building the app

To prepare the build for production:

```bash
yarn build
```

And run it:

```bash
yarn start
```

## Contributing

You can send how many PR's do you want, I'll be glad to analyse and accept them! If you have any questions, suggestions or bug reports [drop here](https://github.com/fariasmateuss/community-user-profile/discussions).

## Contact me

Connect with me at [LinkedIn](https://www.linkedin.com/in/fariasmateuss/).

# License

This project is under the [MIT License](/LICENSE).

Made with ♥ by Mateus V. Farias.
