## Local build

```bash
west build -p -s /home/otsu/zmk/app -d "build/left" -b "nice_nano_v2"  -- -DZMK_CONFIG=/home/otsu/repos/swweeep-zmk/config/ -DSHIELD="swweeep_left nice_view_adapter nice_view" -DZMK_EXTRA_MODULES='/home/otsu/repos/zmk-fingerpunch-keyboards;/home/otsu/repos/zmk-fingerpunch-controllers;/home/otsu/repos/zmk-fingerpunch-vik' && west build -p -s /home/otsu/zmk/app -d "build/right" -b "nice_nano_v2"  -- -DZMK_CONFIG=/home/otsu/repos/swweeep-zmk/config/ -DSHIELD="swweeep_right nice_view_adapter nice_view" -DZMK_EXTRA_MODULES='/home/otsu/repos/zmk-fingerpunch-keyboards;/home/otsu/repos/zmk-fingerpunch-controllers;/home/otsu/repos/zmk-fingerpunch-vik'
```
