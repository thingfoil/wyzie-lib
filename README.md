<p align="center">
  <a href="https://subs.afterstream.org/">
    <img src="https://i.postimg.cc/L5ppKYC5/cclogo.png" height="120">
    <h1 align="center">Libre Subs Lib</h1>
  </a>
</p>

Libre Subs Lib is a package made for easily implementing [Libre Subs](https://subs.afterstream.org/) in your project without all the fuss.

## Configuration

By default, the library uses `https://subs.afterstream.org`. If you want to use your own instance, you can configure it at the start of your application:

```typescript
import { configure } from 'libre-subs-lib';

configure({
  baseUrl: 'https://your-custom-instance.com',
});
```

[Read the docs](https://subs.afterstream.org/)
