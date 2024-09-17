<img src="https://res.cloudinary.com/dbjrx698c/image/upload/v1704611347/logo_w4vxp0.png" width="100" height="100" style="display: block; margin: 0 auto;">

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
