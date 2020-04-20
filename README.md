# ngx-utils-cookies-port

This library is is port of [`@ngx-utils/cookies`](https://github.com/ngx-utils/cookies).
It was created because original library does not support new Angular 9.

Once the original library is updated to new version, this library will be marked as deprecated.

## Installation

```bash
npm install ngx-utils-cookies-port --save
```

## Usage
Follow [original documentation](https://github.com/ngx-utils/cookies#readme).

## Differences from original library
- compatible with Angular version >= `9.0.0`
- created as real Angular library

### Importing modules
The only difference is the way how modules and services are imported.

```typescript
// original library: 
import { BrowserCookiesModule } from '@ngx-utils/cookies/browser';
import { CookiesService } from "@ngx-utils/cookies";

// new: 
import {BrowserCookiesModule} from 'ngx-utils-cookies-port';
import {CookiesService} from 'ngx-utils-cookies-port';

```

## Disclaimer
I'm not the original author of the library nor the source code. The source code was taken (almost unmodified) from [`@ngx-utils/cookies`](https://github.com/ngx-utils/cookies). 
