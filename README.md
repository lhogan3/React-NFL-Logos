# React NFL Logos

![npm](https://img.shields.io/npm/v/react-nfl-logos)

> React components for NFL team logos

![image](https://user-images.githubusercontent.com/11506653/74900567-3f327200-536e-11ea-8dfa-dd1e2b61bd78.png)

## Install

```shell
$ npm install react-nfl-logos
```

## Usage

```js
import React from 'react';
import { ARI } from 'react-nfl-logos';

const Example = () => {
  return <ARI />; // Loads the Arizona Cardinals logo
};

export default Example;
```

or include all icons

```js
import React from 'react';
import * as NFLIcons from 'react-nfl-logos';

const Example = () => {
  return <NFLIcons.ARI />; // Loads the Arizona Cardinals logo
};

export default Example;
```

## Configuration

Size can be easily configured (Default of 100px)

```js
import React from 'react';
import { ARI } from 'react-nfl-logos';

const Example = () => {
  return (
    <div>
      <ARI size={60} />
      <ARI /> // Default of 100px
      <ARI size={140} />
    </div>
  );
};

export default Example;
```

Results in

<img width="324" alt="Screen Shot 2019-07-11 at 5 50 31 PM" src="https://user-images.githubusercontent.com/11506653/74900328-69376480-536d-11ea-9864-58e62a19582b.png">
