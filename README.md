## Asset structure

Images are be placed at `/i/[brand]/[type]/[background]/[color].[extension]`.

| Field        | Description                                        | Possible values                |
| ------------ | -------------------------------------------------- | ------------------------------ |
| `brand`      | What brand are you looking for?                    | `strata`, `strata-source`, `powered-by-strata-source` |
| `type`       | What sort of image do you want?                    | `icon`, `logo`                 |
| `background` | On which background will the image be displayed?\* | `onlight`, `ondark`, `agnostic` |
| `color`      | Do you wish the image to be colored?               | `color`, `mono`                |
| `extension`  | This is self explanatory                           | `svg`, `ai`                    |

\* If you wish to place it over an image, consider using the `ondark` background together with the `mono` color scheme. If this doesn't provide enough contrast, use `onlight`.
