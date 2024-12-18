<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://res.cloudinary.com/dub0dpenl/image/upload/v1731780157/Personal%20Logo/logo-white_e6fujz.png">
  <source media="(prefers-color-scheme: light)" srcset="https://res.cloudinary.com/dub0dpenl/image/upload/v1731780152/Personal%20Logo/logo-dark_qqwrqu.png">
  <img alt="Siam Ahnaf" src="https://res.cloudinary.com/dub0dpenl/image/upload/v1731780152/Personal%20Logo/logo-dark_qqwrqu.png" height="auto" width="240">
</picture>

<div align="center">
  <h1>React Text Loop Typescript</h1>
</div>

> An animated loop of text for your headings or professions. Uses <a href="https://www.react-spring.dev/" target="_blank">@react-spring/web<a> for the transition so it handles super fast animations and spring params.

- SSR Friendly
- Customizable
- TypeScript Support
- Fix Installation problem
- Uses of React 18
- No error with peer deps

## Installation

```shell-script
$ npm i react-text-loop-ts --save
```

## Usage?

```
import { TextLoop } from "react-text-loop-ts";

const Home = () => {
  return (
    <div>
      <TextLoop
          texts={["MERN Stack Developer", "Backend Developer", "Frontend Developer", "NodeJs Developer", "NestJs Developer"]}
          interval={3000}
      />
    </div>
  );
};

export default Home;
```

## Options

| name       |                           Description                           |  Is Required?  |
| :--------- | :-------------------------------------------------------------: |  :-----------:  |
| texts    |          Array of string text, you want to show        |       required        |
| interval    |        Interval times. Default is 3000        |        optional       |

## Issues


You are welcome to create an issue.

## Stay in touch

- Author - [Siam Ahnaf](https://www.siamahnaf.com/)
- Website - [https://www.siamahnaf.com/](https://www.siamahnaf.com/)
- Twitter - [https://twitter.com/siamahnaf198](https://twitter.com/siamahnaf198)
- Github - [https://github.com/siamahnaf198](https://github.com/siamahnaf198)
