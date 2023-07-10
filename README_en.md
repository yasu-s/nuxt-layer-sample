# nuxt-layer-sample

## Overview

- This is a sample using Nuxt3 Layers.

## System Requirements

- Node.js - 20.x
- Yarn - 1.22.x

## Library

- nuxt - 3.6.x

## Usage

```bash
# package installation
$ yarn

# nuxt-app run - http://localhost:3000, http://localhost:3000/layer1, http://localhost:3000/layer2
$ yarn workspace @nuxt-layer-sample/nuxt-app run dev

# layer1 run - http://localhost:3000/layer1
$ yarn workspace @nuxt-layer-sample/layer1 run dev

# layer2 run - http://localhost:3000/layer2
$ yarn workspace @nuxt-layer-sample/layer2 run dev
```

## Reference URL

- https://nuxt.com/docs/getting-started/layers
