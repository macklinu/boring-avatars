# Boring Avatars

Boring avatars is a tiny JavaScript React library that generates custom, SVG-based avatars from any username and color palette.
<a href="https://www.npmjs.com/package/boring-avatars">

![hi](https://badgen.net/npm/v/boring-avatars)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</a>

![boring avatars preview](https://github.com/boringdesigners/boring-avatars/blob/master/public/boring-avatars-preview.png?raw=true)


## Sponsors

[![Clerk logo](https://github.com/boringdesigners/boring-avatars/assets/912236/dc61f436-3fb9-435e-be24-cc406c4847a9)](https://clerk.com/?utm_source=boringavatars&utm_medium=github&utm_campaign=sponsorship)


[Clerk](https://clerk.com/?utm_source=boringavatars&utm_medium=github&utm_campaign=sponsorship) provides drop-in authentication for React and has built-in support for Boring Avatars.


## Install

```
npm install boring-avatars
```

## Usage

```jsx
import Avatar from "boring-avatars";

<Avatar
  size={40}
  name="Maria Mitchell"
  variant="marble"
  colors={["#92A1C6", "#146A7C", "#F0AB3D", "#C271B4", "#C20D90"]}
/>;
```

### Props

| Prop    | Type                                                         |
| ------- | ------------------------------------------------------------ |
| size    | number or string, `40px` (default)                           |
| square  | boolean: `false` (default)                                   |
| title   | boolean: `false` (default)                                   |
| name    | string                                                       |
| variant | oneOf: `marble` (default), `beam`, `pixel`,`sunset`, `ring`, `bauhaus` |
| colors  | array of colors                                              |


## Service

You can embed your boring avatars using the boring avatars source.

To choose a random avatar from a specific user and a color palette, the format follows:

```
https://source.boringavatars.com/marble/120/Maria%20Mitchell?colors=264653,2a9d8f,e9c46a,f4a261,e76f51
```
![Avatar for Maria Mitchell](https://source.boringavatars.com/marble/120/Maria%20Mitchell?colors=264653,2a9d8f,e9c46a,f4a261,e76f51)


For more information, [check out the README](https://github.com/hihayk/boring-avatars-service/blob/main/README.md)

