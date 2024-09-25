# Mars Changelog

Only record what changed in the Mars' version.

## 1.16

- Raise mouse move/scroll speed by 1.5 times.
- Use `keymap.dtsi.erb` to generate the config.

## 1.15

- Set `DIFFICULTY_LEVEL` to `0`, this difficulty should be between 4 and 5.

## 1.14

- Set `DIFFICULTY_LEVEL` to `5` due to v37 increase the holding time for difficulty level 4 to
    250 ms.

## 1.13

- Add sticky `LCTL` & sticky `LALT` using to lower layer using `&sticky_key_oneshot`

## 1.12

- Restore `LSHIFT` to traditional `LSHIFT` instead of one-shot sticky shift
- Restore `T6` to one-shot shift + lower layer

## 1.11

- Set `DIFFICULTY_LEVEL` to `4`

## 1.10

- Upgrade to Glorious Engrammer v37
- Use QWERTY keyboard layout as the main layout (first layer)
- Adjust keyboard layout to me
    - Adjust symbols location
        - `` ` ``
        - `Tab`
        - `-`
        - `\`
        - `=`
        - `(`
        - `)`
        - `[`
        - `]`
        - `Left`
        - `Right`
        - `Up`
        - `Down`
        - `PageUp`
        - `PageDown`
        - `Home`
        - `End`
- Make key location corresponding arrow keys in every mod layers transparent to be able to send
    combined key mapping with arrow keys
- Set `OPERATING_SYSTEM` to `W` to use Windows
- Set `DIFFICULTY_LEVEL` to `0` to use Glorious Engrammer v37's default difficulty level for
    different fingers
