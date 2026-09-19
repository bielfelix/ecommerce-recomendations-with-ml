# E-commerce Recommendation Prototype

This repository captures an early technical stage of the recommendation-system work that later evolved into [NeuroCart](https://github.com/bielfelix/NeuroCart).

It focuses on the frontend flow, user selection, product listing and purchase tracking before the later MongoDB/API and TensorFlow.js work was consolidated in NeuroCart.

## Attribution

The original exercise comes from the external source material published by UNIPDS and Erick Wendel.

Upstream material:
https://github.com/unipds-engenharia-de-ia-aplicada/engenharia-de-software-com-ia-aplicada

The attribution is preserved intentionally. I do not present the base exercise as fully original work.

## What this stage demonstrates

- Browser-based user profile selection
- Product listing
- Purchase-history display
- Purchase tracking with sessionStorage
- Separation between views, controllers and services
- Local development with BrowserSync

## Run

Install dependencies:

```bash
npm ci
```

Start the local server:

```bash
npm start
```

The application is served locally by BrowserSync.

## Project evolution

This repository represents the earlier frontend-oriented stage.

The next architectural stage moved the data layer to a Node.js API and MongoDB:

https://github.com/bielfelix/E-commerce-Recommendation-System-MongoDB-API-Architecture

The more complete current technical implementation version is:

https://github.com/bielfelix/NeuroCart

NeuroCart includes the MongoDB-backed API and the TensorFlow.js recommendation flow.

## Status

Historical technical implementation retained to show architectural progression. It is not presented as a flagship or production recommendation system.


## License and distribution

The upstream source repository is published under CC BY-NC-ND 4.0. Its LICENSE.md states that modified or adapted versions may not be distributed under the NoDerivatives condition. This repository is therefore not presented as a permissively licensed open-source derivative. See [NOTICE.md](NOTICE.md) for the provenance and licensing note.
