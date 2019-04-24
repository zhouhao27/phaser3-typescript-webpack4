# A simple boilerplate with Phaser 3, TypeScript and Webpack 4

## Steps to create the boilerplate

1. Webpack

```
yarn add -D webpack webpack-cli webpack-dev-serve html-webpack-plugin
```

2. TypeScript

```
yarn add -D typescript ts-loader expose-loader
```

3. Phaser

```
yarn add phaser
```

4. Create tsconfig.json

```
{
  "compilerOptions": {
    "target": "ES2016",
    "module": "CommonJS",
    "sourceMap": true,
    "noImplicitAny": false,
    "strict": false
  }
}
```

5. Create webpack.config.js

6. Change package.json to add scripts

```
  "scripts": {
    "dev": "webpack --mode development && webpack-dev-server --mode development",
    "build": "webpack --mode production && webpack-dev-server --mode production"
  },
```

## References

https://github.com/digitsensitive/phaser3-typescript

## Tools

[TexturePacker (free version) for sprite atlases (JSON hash)](https://www.codeandweb.com/texturepacker)

[BFXR](https://www.bfxr.net/)

[Audiosprite](https://github.com/tonistiigi/audiosprite)

[Paint.net](https://www.getpaint.net/)



