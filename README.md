# astro-flamethrower

This project provides an Astro component that integrates the [flamethrower](https://github.com/fireship-io/flamethrower)
client-side router into your site and shows a progress bar on top of the screen while fetching a page.

## Quickstart

Install the project

```
npm install astro-flamethrower
```

and then insert the `<Flamethrower />` component into the `<body>` tag of your layouts.

```astro
---
import { Flamethrower } from "astro-flamethrower";

// ...
---

<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- ... -->
  </head>
  <body>
    <!-- ... -->
    <Flamethrower color="#00ff00" />
  </body>
</html>
```

## Alternatives

- [astro-spa](https://github.com/RafidMuhymin/astro-spa)
- [swup](https://github.com/swup/swup)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

See [LICENSE](LICENSE) for more information.
