# Change Log

## 1.4.9

### Patch Changes

- Updated dependencies
  [[`5cd5cff35`](https://github.com/chakra-ui/chakra-ui/commit/5cd5cff35e4837539d83a2157a07585d461b0aac)]:
  - @chakra-ui/hooks@1.8.5
  - @chakra-ui/portal@1.3.8

## 1.4.8

### Patch Changes

- [`e1fe48cbe`](https://github.com/chakra-ui/chakra-ui/commit/e1fe48cbe37324744cfe6184d785c093cda1125e)
  Thanks [@TimKolberger](https://github.com/TimKolberger)! - Bumped patch
  version for every package to fix release process. Root cause was a bug in our
  CI configuration.
- Updated dependencies
  [[`e1fe48cbe`](https://github.com/chakra-ui/chakra-ui/commit/e1fe48cbe37324744cfe6184d785c093cda1125e)]:
  - @chakra-ui/hooks@1.8.4
  - @chakra-ui/popper@2.4.3
  - @chakra-ui/portal@1.3.7
  - @chakra-ui/react-utils@1.2.3
  - @chakra-ui/utils@1.10.4
  - @chakra-ui/visually-hidden@1.1.6

## 1.4.7

### Patch Changes

- Updated dependencies
  [[`a870e6b94`](https://github.com/chakra-ui/chakra-ui/commit/a870e6b94367b7c6448d5c5c5aa8577e33e15e3a)]:
  - @chakra-ui/utils@1.10.3
  - @chakra-ui/hooks@1.8.3
  - @chakra-ui/portal@1.3.6
  - @chakra-ui/visually-hidden@1.1.5

## 1.4.6

### Patch Changes

- [#5536](https://github.com/chakra-ui/chakra-ui/pull/5536)
  [`a503acabe`](https://github.com/chakra-ui/chakra-ui/commit/a503acabefcaea86cb7f40a6305830f09d2d6083)
  Thanks [@TimKolberger](https://github.com/TimKolberger)! - Bumped patch
  version for every package to fix release process.

- Updated dependencies
  [[`a503acabe`](https://github.com/chakra-ui/chakra-ui/commit/a503acabefcaea86cb7f40a6305830f09d2d6083)]:
  - @chakra-ui/hooks@1.8.2
  - @chakra-ui/popper@2.4.2
  - @chakra-ui/portal@1.3.5
  - @chakra-ui/react-utils@1.2.2
  - @chakra-ui/utils@1.10.2
  - @chakra-ui/visually-hidden@1.1.4

## 1.4.5

### Patch Changes

- [`f6578a1b7`](https://github.com/chakra-ui/chakra-ui/commit/f6578a1b76546c9432d9bcf06acead17d68c62b1)
  Thanks [@TimKolberger](https://github.com/TimKolberger)! - Fix an issue where
  arrow tooltip background color only consider bg props. It considers `bg`,
  `background`, `bgColor` and `backgroundColor` now.

* [#5499](https://github.com/chakra-ui/chakra-ui/pull/5499)
  [`f1d024749`](https://github.com/chakra-ui/chakra-ui/commit/f1d02474983dc8277e767dc729abc3cbb02cfe10)
  Thanks [@noobinthisgame](https://github.com/noobinthisgame)! - allow framer
  motion v6 as peer dependency

* Updated dependencies
  [[`24b4333d0`](https://github.com/chakra-ui/chakra-ui/commit/24b4333d008d149380785f87f4891e28584ff89b)]:
  - @chakra-ui/utils@1.10.1
  - @chakra-ui/hooks@1.8.1
  - @chakra-ui/portal@1.3.4
  - @chakra-ui/visually-hidden@1.1.3

## 1.4.4

### Patch Changes

- Updated dependencies
  [[`cbad002e7`](https://github.com/chakra-ui/chakra-ui/commit/cbad002e7bdb439a0dfeada82ebfb5b529e145fe),
  [`6e259a1f7`](https://github.com/chakra-ui/chakra-ui/commit/6e259a1f7008a00f7be096e6b315cb9d62ef9748),
  [`1537a725f`](https://github.com/chakra-ui/chakra-ui/commit/1537a725fbc7f84979e374f546bda625fc685ac3)]:
  - @chakra-ui/hooks@1.8.0
  - @chakra-ui/utils@1.10.0
  - @chakra-ui/visually-hidden@1.1.2
  - @chakra-ui/portal@1.3.3

## 1.4.3

### Patch Changes

- [#5228](https://github.com/chakra-ui/chakra-ui/pull/5228)
  [`f05f56b9a`](https://github.com/chakra-ui/chakra-ui/commit/f05f56b9a9abe27947ed32ae39d01602e1be8a76)
  Thanks [@seancwalsh](https://github.com/seancwalsh)! - Fix broken link in
  Tooltip's JSDoc comment

- Updated dependencies
  [[`801008e27`](https://github.com/chakra-ui/chakra-ui/commit/801008e276812a6f94f2f5dc634bcbfe01d23026),
  [`8a0e5bdbc`](https://github.com/chakra-ui/chakra-ui/commit/8a0e5bdbccb7fa10dd4cd7b909ca60991fce81a0)]:
  - @chakra-ui/hooks@1.7.2
  - @chakra-ui/portal@1.3.2

## 1.4.2

### Patch Changes

- [#5139](https://github.com/chakra-ui/chakra-ui/pull/5139)
  [`c20aa919e`](https://github.com/chakra-ui/chakra-ui/commit/c20aa919e4fa4d89a2c9be603fa60f851576558b)
  Thanks [@mlajtos](https://github.com/mlajtos)! - Prevent `onKeyDown` callback
  from de/registering on every call of `useTooltip`

## 1.4.1

### Patch Changes

- [#5075](https://github.com/chakra-ui/chakra-ui/pull/5075)
  [`b28142946`](https://github.com/chakra-ui/chakra-ui/commit/b281429462a099b7fd7f9352e837cd28d1a2da0e)
  Thanks [@cschroeter](https://github.com/cschroeter)! - Update babel config to
  transpile soruces for older browsers. This fixes issues with CRA and
  Storybook.
- Updated dependencies
  [[`b28142946`](https://github.com/chakra-ui/chakra-ui/commit/b281429462a099b7fd7f9352e837cd28d1a2da0e)]:
  - @chakra-ui/hooks@1.7.1
  - @chakra-ui/popper@2.4.1
  - @chakra-ui/portal@1.3.1
  - @chakra-ui/react-utils@1.2.1
  - @chakra-ui/utils@1.9.1
  - @chakra-ui/visually-hidden@1.1.1

## 1.4.0

### Minor Changes

- [#4991](https://github.com/chakra-ui/chakra-ui/pull/4991)
  [`6095eaf9a`](https://github.com/chakra-ui/chakra-ui/commit/6095eaf9ac64a7e4d9f934bcb530bae2a92111a6)
  Thanks [@segunadebayo](https://github.com/segunadebayo)! - Update build system
  we use from a custom babel cli setup to
  [preconstruct](https://preconstruct.tools/).

  The previous build system transpiles the code in `src` directory to `dist/esm`
  and `dist/cjs` keeping the same file structure. The new build system merges
  all files in `src` and transpiles to a single `esm` and `cjs` file.

  **Potential Breaking Change:** The side effect of this is that, if you
  imported any function, component or hook using the **undocumented** approach
  like
  `import { useOutsideClick } from "@chakra-ui/hooks/dist/use-outside-click"`,
  you'll notice that the this doesn't work anymore.

  Here's how to resolve it:

  ```jsx live=false
  // Won't work 🎇
  import { useOutsideClick } from "@chakra-ui/hooks/dist/use-outside-click"

  // Works ✅
  import { useOutsideClick } from "@chakra-ui/hooks"
  ```

  If this affected your project, we recommend that you import hooks, functions
  or components the way it's shown in the documentation. This will help keep
  your project future-proof.

### Patch Changes

- Updated dependencies
  [[`6095eaf9a`](https://github.com/chakra-ui/chakra-ui/commit/6095eaf9ac64a7e4d9f934bcb530bae2a92111a6)]:
  - @chakra-ui/hooks@1.7.0
  - @chakra-ui/popper@2.4.0
  - @chakra-ui/portal@1.3.0
  - @chakra-ui/react-utils@1.2.0
  - @chakra-ui/utils@1.9.0
  - @chakra-ui/visually-hidden@1.1.0

## 1.3.14

### Patch Changes

- [`04774e219`](https://github.com/chakra-ui/chakra-ui/commit/04774e2196b9f3e8edd77f779e8c15981e8d8135)
  [#4965](https://github.com/chakra-ui/chakra-ui/pull/4965) Thanks
  [@takethefake](https://github.com/takethefake)! - Allow usage of
  `framer-motion` 5.x in `peerDependency`

- Updated dependencies
  [[`c3f016149`](https://github.com/chakra-ui/chakra-ui/commit/c3f01614929d2f68a39cf78111d17f4f4c684706)]:
  - @chakra-ui/popper@2.3.1

## 1.3.13

### Patch Changes

- Updated dependencies
  [[`5fe9b552b`](https://github.com/chakra-ui/chakra-ui/commit/5fe9b552bcae55935d1ab8ffde86b701075e6e6a),
  [`cd0893c56`](https://github.com/chakra-ui/chakra-ui/commit/cd0893c561d8c72b69db7c03d10adae752468a4f)]:
  - @chakra-ui/hooks@1.6.2
  - @chakra-ui/utils@1.8.4
  - @chakra-ui/portal@1.2.11
  - @chakra-ui/visually-hidden@1.0.16

## 1.3.12

### Patch Changes

- Updated dependencies
  [[`c06d242c6`](https://github.com/chakra-ui/chakra-ui/commit/c06d242c672a10f93fab4dc2321143beae2db669),
  [`a9d1dc4ac`](https://github.com/chakra-ui/chakra-ui/commit/a9d1dc4ac874825f292d874ad4eadaf060fed436),
  [`5b4d8ef24`](https://github.com/chakra-ui/chakra-ui/commit/5b4d8ef24017dab1d69aeb5016b53366bdb3bcfd)]:
  - @chakra-ui/utils@1.8.3
  - @chakra-ui/hooks@1.6.1
  - @chakra-ui/portal@1.2.10
  - @chakra-ui/visually-hidden@1.0.15

## 1.3.11

### Patch Changes

- Updated dependencies
  [[`4146a9051`](https://github.com/chakra-ui/chakra-ui/commit/4146a9051a5151532503e31c464193e9d118dd26)]:
  - @chakra-ui/popper@2.3.0

## 1.3.10

### Patch Changes

- Updated dependencies
  [[`28af4c030`](https://github.com/chakra-ui/chakra-ui/commit/28af4c0308e234871548c0857e946e33ff18a130)]:
  - @chakra-ui/hooks@1.6.0
  - @chakra-ui/portal@1.2.9

## 1.3.9

### Patch Changes

- [`df57f448f`](https://github.com/chakra-ui/chakra-ui/commit/df57f448ff1de6eded6647f73950e8978612316c)
  [#4442](https://github.com/chakra-ui/chakra-ui/pull/4442) Thanks
  [@5ebastianMeier](https://github.com/5ebastianMeier)! - Fix tooltips not
  closing when openDelay is set

- Updated dependencies
  [[`4c1071969`](https://github.com/chakra-ui/chakra-ui/commit/4c1071969a9b41a952b374f9990ac0bb89d24fa0),
  [`43f66097b`](https://github.com/chakra-ui/chakra-ui/commit/43f66097b39f1c37a4627dd6ca8a85555f35b95c)]:
  - @chakra-ui/utils@1.8.2
  - @chakra-ui/hooks@1.5.5
  - @chakra-ui/portal@1.2.8
  - @chakra-ui/visually-hidden@1.0.14

## 1.3.8

### Patch Changes

- Updated dependencies
  [[`4a1e4d93b`](https://github.com/chakra-ui/chakra-ui/commit/4a1e4d93b0a07df7266d40bb66039385b158d3d1)]:
  - @chakra-ui/utils@1.8.1
  - @chakra-ui/hooks@1.5.4
  - @chakra-ui/portal@1.2.7
  - @chakra-ui/visually-hidden@1.0.13

## 1.3.7

### Patch Changes

- Updated dependencies
  [[`4c157e320`](https://github.com/chakra-ui/chakra-ui/commit/4c157e320a73b08eb89a44831a7cf434fb403bad),
  [`aa374ffcb`](https://github.com/chakra-ui/chakra-ui/commit/aa374ffcb4003efd88eb6a62e10723ea9fbfa3d0),
  [`5afa7ef49`](https://github.com/chakra-ui/chakra-ui/commit/5afa7ef49c7e3b01bce932e252865226b9511b39)]:
  - @chakra-ui/portal@1.2.6
  - @chakra-ui/hooks@1.5.3
  - @chakra-ui/popper@2.2.1

## 1.3.6

### Patch Changes

- [`5e24481fc`](https://github.com/chakra-ui/chakra-ui/commit/5e24481fc73b0097d0bac900479d7cc145a92670)
  [#4026](https://github.com/chakra-ui/chakra-ui/pull/4026) Thanks
  [@dodas](https://github.com/dodas)! - Add `enabled` option to `usePopper`
  hook.

  The `popper.js` instance will not be created until this option is `true`.

  `Menu`, `Popover` and `Tooltip` components now use this option, so the
  `popper.js` instance is created only once the popper is open. This should
  significantly improve render and scroll performance.

- Updated dependencies
  [[`5e24481fc`](https://github.com/chakra-ui/chakra-ui/commit/5e24481fc73b0097d0bac900479d7cc145a92670)]:
  - @chakra-ui/popper@2.2.0

## 1.3.5

### Patch Changes

- Updated dependencies
  [[`d0f50a46e`](https://github.com/chakra-ui/chakra-ui/commit/d0f50a46ea6c2bcf06d8cad8b9b3994fd934be01),
  [`b479ff22e`](https://github.com/chakra-ui/chakra-ui/commit/b479ff22ea10c1a1393224c37c36aa6ceabc4aab),
  [`07d15eab4`](https://github.com/chakra-ui/chakra-ui/commit/07d15eab480724f8fee1a09b7cecdf1e968d9ddd),
  [`d0f50a46e`](https://github.com/chakra-ui/chakra-ui/commit/d0f50a46ea6c2bcf06d8cad8b9b3994fd934be01)]:
  - @chakra-ui/utils@1.8.0
  - @chakra-ui/hooks@1.5.2
  - @chakra-ui/portal@1.2.5
  - @chakra-ui/visually-hidden@1.0.12

## 1.3.4

### Patch Changes

- Updated dependencies
  [[`82f08867f`](https://github.com/chakra-ui/chakra-ui/commit/82f08867fa4825d647a3b9cc805220d9364f2f3f),
  [`e9ac4cc76`](https://github.com/chakra-ui/chakra-ui/commit/e9ac4cc7629cd79efc753b4e3353bacdad46cd7d)]:
  - @chakra-ui/react-utils@1.1.2
  - @chakra-ui/utils@1.7.0
  - @chakra-ui/hooks@1.5.1
  - @chakra-ui/popper@2.1.2
  - @chakra-ui/portal@1.2.4
  - @chakra-ui/visually-hidden@1.0.11

## 1.3.3

### Patch Changes

- Updated dependencies
  [[`0974e547c`](https://github.com/chakra-ui/chakra-ui/commit/0974e547c29e4efc1ba4d1eb1507d0dad7d7a77a),
  [`59ea894a7`](https://github.com/chakra-ui/chakra-ui/commit/59ea894a7e03d16cd7a1b89d00816eafa9fab65d),
  [`384902e35`](https://github.com/chakra-ui/chakra-ui/commit/384902e35b186c8c8154b9569455c27f72ee0f6f)]:
  - @chakra-ui/utils@1.6.0
  - @chakra-ui/hooks@1.5.0
  - @chakra-ui/portal@1.2.3
  - @chakra-ui/visually-hidden@1.0.10

## 1.3.2

### Patch Changes

- [`3310f952e`](https://github.com/chakra-ui/chakra-ui/commit/3310f952efc6a196b12ffff1a0951683e0b0b6ff)
  Thanks [@segunadebayo](https://github.com/segunadebayo)! - use prop-getters
  from use-popper to prevent ssr content shift

* [`a73198529`](https://github.com/chakra-ui/chakra-ui/commit/a7319852908f68596600da799ef08a0e7dbb468e)
  [#3775](https://github.com/chakra-ui/chakra-ui/pull/3775) Thanks
  [@tomchentw](https://github.com/tomchentw)! - Add missing dependency issue of
  `@chakra-ui/react-utils`

* Updated dependencies
  [[`8b5eb9654`](https://github.com/chakra-ui/chakra-ui/commit/8b5eb9654affe562795d38a19f732f84732a949d),
  [`d1532f0b7`](https://github.com/chakra-ui/chakra-ui/commit/d1532f0b72c36d0609ee4510613d7c76f4f9c113),
  [`1615af488`](https://github.com/chakra-ui/chakra-ui/commit/1615af4881a6f37cffb7ea15078cf7ab6a4e4c79)]:
  - @chakra-ui/utils@1.5.2
  - @chakra-ui/hooks@1.4.0
  - @chakra-ui/popper@2.1.1
  - @chakra-ui/portal@1.2.2
  - @chakra-ui/visually-hidden@1.0.9

## 1.3.1

### Patch Changes

- [`2287d82e3`](https://github.com/chakra-ui/chakra-ui/commit/2287d82e31744cd289aaf524bb9961e46003c404)
  [#3715](https://github.com/chakra-ui/chakra-ui/pull/3715) Thanks
  [@with-heart](https://github.com/with-heart)! - Resolved a peer dependency
  resolution issue reported by yarn2, npm7, and other more modern package
  managers
- Updated dependencies
  [[`1a04a41bd`](https://github.com/chakra-ui/chakra-ui/commit/1a04a41bd2285069011a738fff422ba1a6fcce94),
  [`75817ec42`](https://github.com/chakra-ui/chakra-ui/commit/75817ec428ca3c078660a7c7f2a1c1b578c474df),
  [`e481ba491`](https://github.com/chakra-ui/chakra-ui/commit/e481ba4914a7f163d93d4c22e2e457f1afb08721)]:
  - @chakra-ui/utils@1.5.1
  - @chakra-ui/popper@2.1.0
  - @chakra-ui/hooks@1.3.1
  - @chakra-ui/portal@1.2.1
  - @chakra-ui/visually-hidden@1.0.8

## 1.3.0

### Minor Changes

- [`b724a9dd9`](https://github.com/chakra-ui/chakra-ui/commit/b724a9dd9429d02c0b2c7f7deac66d3553100bdc)
  [#3674](https://github.com/chakra-ui/chakra-ui/pull/3674) Thanks
  [@codebender828](https://github.com/codebender828)! - Extract all React based
  utilities and types into `@chakra-ui/react-utils`

### Patch Changes

- Updated dependencies
  [[`623e782e8`](https://github.com/chakra-ui/chakra-ui/commit/623e782e80124297740a109e5c6c58cddc35b2eb),
  [`a58b724e9`](https://github.com/chakra-ui/chakra-ui/commit/a58b724e9c8656044f866b658f378662f2a44b46),
  [`b724a9dd9`](https://github.com/chakra-ui/chakra-ui/commit/b724a9dd9429d02c0b2c7f7deac66d3553100bdc)]:
  - @chakra-ui/hooks@1.3.0
  - @chakra-ui/utils@1.5.0
  - @chakra-ui/portal@1.2.0
  - @chakra-ui/visually-hidden@1.0.7
  - @chakra-ui/popper@2.0.1

## 1.2.0

### Minor Changes

- [`64e8466b5`](https://github.com/chakra-ui/chakra-ui/commit/64e8466b528a027c915b7d2d5f474b08a0800e92)
  [#3623](https://github.com/chakra-ui/chakra-ui/pull/3623) Thanks
  [@with-heart](https://github.com/with-heart)! - Added support for
  `framer-motion` v4

### Patch Changes

- [`91ef14839`](https://github.com/chakra-ui/chakra-ui/commit/91ef148397187010804eb8f30307d2ec94c32c5b)
  [#3583](https://github.com/chakra-ui/chakra-ui/pull/3583) Thanks
  [@segunadebayo](https://github.com/segunadebayo)! - - Refactor arrow
  components to use `data-popper-arrow` and `data-popper-arrow-inner` to define
  the arrow elements. This is used within the modifiers to update the arrow
  styles/position positioning.

  - Change `arrowSize` and `arrowShadowColor` to use CSS custom properties
    instead of passing it to `usePopper`.

  - Update component themes to use `--popper-arrow-bg` to set the background for
    the popper's arrow element.

- Updated dependencies
  [[`e748219f3`](https://github.com/chakra-ui/chakra-ui/commit/e748219f300f0c51b0eb304fce38b014d7bcbc86),
  [`9c143bfe5`](https://github.com/chakra-ui/chakra-ui/commit/9c143bfe5bbf180929fabb0a1b4c18d40f7fd3fc),
  [`91ef14839`](https://github.com/chakra-ui/chakra-ui/commit/91ef148397187010804eb8f30307d2ec94c32c5b),
  [`91ef14839`](https://github.com/chakra-ui/chakra-ui/commit/91ef148397187010804eb8f30307d2ec94c32c5b)]:
  - @chakra-ui/hooks@1.2.0
  - @chakra-ui/utils@1.4.0
  - @chakra-ui/popper@2.0.0
  - @chakra-ui/visually-hidden@1.0.6
  - @chakra-ui/portal@1.1.3

## 1.1.3

### Patch Changes

- Updated dependencies
  [[`83ae62905`](https://github.com/chakra-ui/chakra-ui/commit/83ae62905935fdb3104380d6fd845159b00095fa),
  [`e1924c621`](https://github.com/chakra-ui/chakra-ui/commit/e1924c62182969a109b4900b05932caa1b73ed99),
  [`87cc23e14`](https://github.com/chakra-ui/chakra-ui/commit/87cc23e14814e02cbbfc9737c2356cef682ddd5d)]:
  - @chakra-ui/hooks@1.1.5
  - @chakra-ui/popper@1.1.5
  - @chakra-ui/utils@1.3.0
  - @chakra-ui/visually-hidden@1.0.5
  - @chakra-ui/portal@1.1.2

## 1.1.2

### Patch Changes

- Updated dependencies
  [[`51ad518e2`](https://github.com/chakra-ui/chakra-ui/commit/51ad518e22642076485bee3dd1f99acbf025161b)]:
  - @chakra-ui/popper@1.1.4

## 1.1.1

### Patch Changes

- [`a023a269f`](https://github.com/chakra-ui/chakra-ui/commit/a023a269ffe0efdae74be3de28e41790c9a5ca8a)
  [#3278](https://github.com/chakra-ui/chakra-ui/pull/3278) Thanks
  [@dodas](https://github.com/dodas)! - Fixed an issue where a `Tooltip` with
  negative `gutter` causes flickering on hover.
- Updated dependencies
  [[`ff4a36bca`](https://github.com/chakra-ui/chakra-ui/commit/ff4a36bca11cc177830f6f1da13700acd1e3a087),
  [`483687237`](https://github.com/chakra-ui/chakra-ui/commit/483687237f2c4fed05dc6a79693f307c601c1285),
  [`61962345c`](https://github.com/chakra-ui/chakra-ui/commit/61962345c5b1c862445c16c586e304b28c376c9a)]:
  - @chakra-ui/utils@1.2.0
  - @chakra-ui/visually-hidden@1.0.4
  - @chakra-ui/hooks@1.1.4
  - @chakra-ui/popper@1.1.3
  - @chakra-ui/portal@1.1.1

## 1.1.0

### Minor Changes

- [`14be4be2c`](https://github.com/chakra-ui/chakra-ui/commit/14be4be2c6f64896612cb05d7e56c2c5e4015335)
  [#3210](https://github.com/chakra-ui/chakra-ui/pull/3210) Thanks
  [@segunadebayo](https://github.com/segunadebayo)! - Add support for forwarding
  props to the underlying `Portal` component. Pass the `portalProps` prop to
  achive this.

  The 2 props you can pass to the portalProps are:

  - `containerRef`: `ref` for the element where to mount the portal
  - `appendToParentPortal`: If `false`, it'll opt out of portal nesting

  ```jsx
  <Modal portalProps={{ containerRef: ref }}>
    <ModalOverlay />
    <ModalContent>
      <Box>Modal content</Box>
      <Tooltip portalProps={{ appendToParentPortal: false }}>
        Some tooltip
      </Tooltip>
    </ModalContent>
  </Modal>
  ```

* [`90c7a4fbf`](https://github.com/chakra-ui/chakra-ui/commit/90c7a4fbfde69c01395ffe2876d7348dd72ea65a)
  [#3092](https://github.com/chakra-ui/chakra-ui/pull/3092) Thanks
  [@TimKolberger](https://github.com/TimKolberger)! - - Improved theme typing in
  order to provide a better autocomplete experience
  - Fixed a type issue where pseudo style props like `_hover` and `_active`
    didn't allow regular css properties

### Patch Changes

- Updated dependencies
  [[`b572bceed`](https://github.com/chakra-ui/chakra-ui/commit/b572bceedd9fb0c41c65118f0d9ba672791932ca),
  [`e41e6b81b`](https://github.com/chakra-ui/chakra-ui/commit/e41e6b81bf6943fef9b34e5ddd31ee57b416a426)]:
  - @chakra-ui/hooks@1.1.3
  - @chakra-ui/portal@1.1.0
  - @chakra-ui/popper@1.1.2

## 1.0.6

### Patch Changes

- Updated dependencies
  [[`002a4361`](https://github.com/chakra-ui/chakra-ui/commit/002a4361bd738bef49e021a2fff2b9b6a9af5815),
  [`31881da7`](https://github.com/chakra-ui/chakra-ui/commit/31881da7314c9c464d080b7dd83edd59d8786b7c)]:
  - @chakra-ui/hooks@1.1.2
  - @chakra-ui/portal@1.0.6
  - @chakra-ui/popper@1.1.1

## 1.0.5

### Patch Changes

- Updated dependencies
  [[`02855588`](https://github.com/chakra-ui/chakra-ui/commit/02855588a4ffbc6573768052e53cc538361e91ee),
  [`0d620f1d`](https://github.com/chakra-ui/chakra-ui/commit/0d620f1d46b9c72c9aef3bb15a691a249ace2eb4),
  [`032f1678`](https://github.com/chakra-ui/chakra-ui/commit/032f16788553b84685de61af5f021c395e09648f)]:
  - @chakra-ui/hooks@1.1.1
  - @chakra-ui/portal@1.0.5
  - @chakra-ui/popper@1.1.0

## 1.0.4

### Patch Changes

- Updated dependencies
  [[`8b87406c`](https://github.com/chakra-ui/chakra-ui/commit/8b87406c3132586be3393117eef80d47ec82fc54),
  [`8b87406c`](https://github.com/chakra-ui/chakra-ui/commit/8b87406c3132586be3393117eef80d47ec82fc54),
  [`8b87406c`](https://github.com/chakra-ui/chakra-ui/commit/8b87406c3132586be3393117eef80d47ec82fc54)]:
  - @chakra-ui/hooks@1.1.0
  - @chakra-ui/utils@1.1.0
  - @chakra-ui/popper@1.0.3
  - @chakra-ui/portal@1.0.4
  - @chakra-ui/visually-hidden@1.0.3

## 1.0.3

### Patch Changes

- Updated dependencies
  [[`a98817de`](https://github.com/chakra-ui/chakra-ui/commit/a98817de0849bf9eec89fae3faf4fbe085f21011)]:
  - @chakra-ui/portal@1.0.3

## 1.0.2

### Patch Changes

- [`5bff79a1`](https://github.com/chakra-ui/chakra-ui/commit/5bff79a1ba6989d279fc432d5040c72cd75b392e)
  Thanks [@jmiazga](https://github.com/jmiazga)! - Updated framer-motion
  peerDependencies to v3

- Updated dependencies
  [[`e73878ee`](https://github.com/chakra-ui/chakra-ui/commit/e73878ee686c11d3f94ad6ac61b19ae9508d75a5)]:
  - @chakra-ui/utils@1.0.2
  - @chakra-ui/visually-hidden@1.0.2
  - @chakra-ui/hooks@1.0.2
  - @chakra-ui/popper@1.0.2
  - @chakra-ui/portal@1.0.2

## 1.0.1

### Patch Changes

- Updated dependencies
  [[`5c482483`](https://github.com/chakra-ui/chakra-ui/commit/5c482483ce24fc798540c9792a15e06772eae213),
  [`204ff7e3`](https://github.com/chakra-ui/chakra-ui/commit/204ff7e39dd37003786194704b36069ef94d56a6)]:
  - @chakra-ui/utils@1.0.1
  - @chakra-ui/hooks@1.0.1
  - @chakra-ui/popper@1.0.1
  - @chakra-ui/portal@1.0.1
  - @chakra-ui/visually-hidden@1.0.1

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0 (2020-11-13)

**Note:** Version bump only for package @chakra-ui/tooltip

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-rc.8 (2020-10-29)

### Bug Fixes

- **toast:** allow custom render in update
  ([eb8bff9](https://github.com/chakra-ui/chakra-ui/commit/eb8bff911e6ec9de0165ab1e8f5ca10d5e022459)),
  closes [#2362](https://github.com/chakra-ui/chakra-ui/issues/2362)

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-rc.7 (2020-10-25)

**Note:** Version bump only for package @chakra-ui/tooltip

# 1.0.0-rc.6 (2020-10-25)

**Note:** Version bump only for package @chakra-ui/tooltip

# 1.0.0-rc.5 (2020-09-27)

**Note:** Version bump only for package @chakra-ui/tooltip

# 1.0.0-rc.4 (2020-09-25)

**Note:** Version bump only for package @chakra-ui/tooltip

# 1.0.0-rc.3 (2020-08-30)

**Note:** Version bump only for package @chakra-ui/tooltip

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-rc.2 (2020-08-09)

**Note:** Version bump only for package @chakra-ui/tooltip

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-rc.1](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/tooltip@1.0.0-rc.0...@chakra-ui/tooltip@1.0.0-rc.1) (2020-08-06)

### Bug Fixes

- **variables:** drop unused imports
  ([552b2e9](https://github.com/chakra-ui/chakra-ui/commit/552b2e9b7510963db509a5724af5361ef07c8ecb))
- stack key issue and yarn2 deps issue
  ([d6cb6b8](https://github.com/chakra-ui/chakra-ui/commit/d6cb6b8fd964729efdf41b1e29c888a3c101316c))
- tooltip memory leak
  ([bac0823](https://github.com/chakra-ui/chakra-ui/commit/bac082373de41243b84f19385d45427afcb4f2db))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-rc.0](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/tooltip@1.0.0-next.7...@chakra-ui/tooltip@1.0.0-rc.0) (2020-07-26)

**Note:** Version bump only for package @chakra-ui/tooltip

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-next.7](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/tooltip@1.0.0-next.6...@chakra-ui/tooltip@1.0.0-next.7) (2020-07-26)

**Note:** Version bump only for package @chakra-ui/tooltip

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-next.6](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/tooltip@1.0.0-next.5...@chakra-ui/tooltip@1.0.0-next.6) (2020-07-15)

**Note:** Version bump only for package @chakra-ui/tooltip

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-next.5](https://github.com/chakra-ui/chakra-ui/compare/@chakra-ui/tooltip@1.0.0-next.4...@chakra-ui/tooltip@1.0.0-next.5) (2020-07-15)

### Bug Fixes

- **tooltip:** implicit object for onClose and onOpen
  ([c20fd6f](https://github.com/chakra-ui/chakra-ui/commit/c20fd6ffa45d47d8f138193292897fb755494fdc))
- **tooltip:** rename show and hide to open and close
  ([b612144](https://github.com/chakra-ui/chakra-ui/commit/b612144c179f3076113dac495f8b4af982b16cd4))

### Features

- add popover transition
  ([73d8c4f](https://github.com/chakra-ui/chakra-ui/commit/73d8c4fc9c676c95232cd259f59cce7d38eff94b))
- add transition for modal
  ([dda931b](https://github.com/chakra-ui/chakra-ui/commit/dda931bea7444c3f83392eebf1c34dd571a0dbbc))
- **tooltip-disable:** add is-disabled prop to tooltip component
  ([29c182b](https://github.com/chakra-ui/chakra-ui/commit/29c182b35dc139f09b931fafec84c0a20683ee8f))
- **tooltip-disable:** add test for is-disabled prop on tooltip
  ([dbac9dd](https://github.com/chakra-ui/chakra-ui/commit/dbac9dd7a7ba0bda7a248eb606a98019fa44ce82))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-next.4 (2020-07-01)

### Bug Fixes

- [#891](https://github.com/chakra-ui/chakra-ui/issues/891)
  ([e107acc](https://github.com/chakra-ui/chakra-ui/commit/e107acc8487898a965b0d695c1da71f46fc56d5e))
- GripProps export conflict
  ([79b15b1](https://github.com/chakra-ui/chakra-ui/commit/79b15b1e92f4f1280f12fca5742f94193af07dd4))
- ts issue with sx prop
  ([d3b1340](https://github.com/chakra-ui/chakra-ui/commit/d3b1340cb255937927b4d4c56ce218141570b951))
- **tooltip:** don't show tooltip if label is empty
  [#601](https://github.com/chakra-ui/chakra-ui/issues/601)
  ([2905129](https://github.com/chakra-ui/chakra-ui/commit/2905129c858bfd16446fd756f2694b54dc7fac81))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-next.3 (2020-06-28)

### Bug Fixes

- [#891](https://github.com/chakra-ui/chakra-ui/issues/891)
  ([e107acc](https://github.com/chakra-ui/chakra-ui/commit/e107acc8487898a965b0d695c1da71f46fc56d5e))
- GripProps export conflict
  ([79b15b1](https://github.com/chakra-ui/chakra-ui/commit/79b15b1e92f4f1280f12fca5742f94193af07dd4))
- ts issue with sx prop
  ([d3b1340](https://github.com/chakra-ui/chakra-ui/commit/d3b1340cb255937927b4d4c56ce218141570b951))
- **tooltip:** don't show tooltip if label is empty
  [#601](https://github.com/chakra-ui/chakra-ui/issues/601)
  ([2905129](https://github.com/chakra-ui/chakra-ui/commit/2905129c858bfd16446fd756f2694b54dc7fac81))

# Change Log

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.0.0-next.2 (2020-06-21)

### Bug Fixes

- [#891](https://github.com/chakra-ui/chakra-ui/issues/891)
  ([e107acc](https://github.com/chakra-ui/chakra-ui/commit/e107acc8487898a965b0d695c1da71f46fc56d5e))
- GripProps export conflict
  ([79b15b1](https://github.com/chakra-ui/chakra-ui/commit/79b15b1e92f4f1280f12fca5742f94193af07dd4))
- **tooltip:** don't show tooltip if label is empty
  [#601](https://github.com/chakra-ui/chakra-ui/issues/601)
  ([2905129](https://github.com/chakra-ui/chakra-ui/commit/2905129c858bfd16446fd756f2694b54dc7fac81))
