# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.2] - 2021-10-24

[0.3.2]: ../../../compare/917ed643ddf678d62a24862076e66faa0055ec8d...e3a468025b49c3b7a4989b20fb8317ab8f1ab986

### Features

- *core:* New typography font classes for many font weights and styles ([5fb4edf](5fb4edf4b67e1d0902396ef93d76a0fefc27c1f1))

### Improvements

- *core:* Add strong and em tags to general typography class ([ce1895f](ce1895f59c873b5826dfd2014cffe425b5f3e5d2))
- *core:* Optimize display classes for  property one-liners ([e3a4680](e3a468025b49c3b7a4989b20fb8317ab8f1ab986))
- *defaults:* Integrate serif class into typefaces ([a705063](a7050634ad11ca08f20da68cf3f7a05f0f55a6b3))

### Refactoring Updates

- *core:* Remove obsolete bootstrap code and old tooltip design ([9693245](9693245a3128b53b90881c3a16627754cde7e836))
- *core:* Move misc utilities from other files to ([e53560b](e53560b35f706945ae682a3d57fc09b01deecb14))
- *defaults:* Move  as  to core ([d8fc7a3](d8fc7a35a875a1da48f344d35bb242a78b101164))

<!-- CHANGELOG SPLIT MARKER -->
## [0.3.1] - 2021-10-24

[0.3.1]: ../../../compare/e796c8965670e778cc349c17a304ee3883a9268c...917ed643ddf678d62a24862076e66faa0055ec8d

### Bug Fixes

- *comps:* Fix badge rendering with muse coloring ([89d6482](89d6482c7559126bc1ca68cd2b628035cbb25d15))

### Improvements

- *comps:* Refactor alert to optimize close button globally ([47ef0bf](47ef0bf2899a58b29ba43f10cb8aa6cc6d3f8cf6))

### Refactoring Updates

- *core:* Comment unused variables, to be deprecated in future versions ([4f6c0ce](4f6c0ce5fd501adeb970aa271c1096e050089235))

<!-- CHANGELOG SPLIT MARKER -->
## [0.3.0] - 2021-10-20

[0.3.0]: ../../../releases/tag/v0.3.0

### Bug Fixes

- *comps:* Fix `display` weight and `letter-spacing` in card heading ([858821f](858821f241326126fa2ff7bf9dade4e04b9d1f4e))
- *comps:* Fix link color for good hover contrast ([694058e](694058e5cb75ba2f247083fff73dea5c8f732144))
- *comps:* Increase tags spacing for mobile devices ([02fa0df](02fa0dfad8f7266ba8eb3a3db8bb2cc5579ebc7a))
- *comps:* Fix low contrast borders of cards with new auto margin utils ([3564276](35642762572fc71e00b4ef2e250ffc1de4d2f968))
- *core:* Fix container grid xs screen size to 90vw with minor tweaks ([19970e1](19970e10649296444aefcaf4e3320b6e3b01ee34))
- *core:* Fix xs container width to 300px ([a6e6af3](a6e6af3e0155f3938022125900c650b10530e270))
- *core:* Fix navbar `padding` and height issues with 4k viewport ([651a28a](651a28ad1da5856179918e55dc600f024c3dc609))
- *defaults:* Focus outline showing at unprecedented viewports ([0264acb](0264acb3fca5a9200dcd0f8450708ed25ba87cc3))
- *defaults:* Fix content styling with formatting of other objects ([db73a31](db73a3131aed3cf32ba8a214dddc0005527b4182))
- *prefabs:* Change tag from `h4` to `h3` for a11y support ([513e31e](513e31e9fb019b141b0ab53d27f6b8c9c1a5938d))

### Features

- *cliff:* Add N3N cliff config file for changelog generation ([1b01641](1b016418d4cafc1b60d37e833300a326436133e6))
- *comps:* Add alerts with change in mizui unified saturation engine (muse) ([25e9073](25e907363db51fdca95e46c8eb32936989b787af))
- *comps:* Add responsive navigation bar with hamburgers ([46dc763](46dc763850af04c4babd85cc10932a3b76fb4cfc))
- *comps:* Add cards from mizui v0.2.5 with spacing classes ([42892ab](42892abe7ff4af3de9f6fe9637a8d17b127ba2ca))
- *comps:* Add `dropdown` class with mobile viewport support ([684f2a0](684f2a00f340b07148bb401c27fa5a916f53d84b))
- *comps:* Add outline and arrow button styles with faster transitions ([83df897](83df8973bf0760843030289833d3e4740105becc))
- *core:* Add rfs mixin from bootstrap along with many small changes ([a0328e7](a0328e74a5b1279e8e497b6dea14c74042f69100))
- *defaults:* Add typeface classes for global content with navbar gap fix ([199b07e](199b07e7ac51e57871ba3b2a84a7ec8544b1c351))
- *defaults:* Add content style for pages to improve readability ([b0b4a09](b0b4a09ba9dad0fe93e477782e68c76c22625de2))
- *prefabs:* Add footer prefabs with footer comps ([94e8828](94e882880ad4da72bad267e361b56a26cf745d56))
- *prefabs:* Add 404 site prefabs for error pages ([e2c5e98](e2c5e9864753e1efee9198d3830e3a412b260b6c))
- *prefabs:* Add jumbotron prefabs including its global vars ([9311991](93119919c7ed7768432652234dd218482234b90c))

### Improvements

- *app:* Add user specific application components ([7ee1d3f](7ee1d3f3fd61bfc7a0e8429b01de71da3217dbe3))
- *comps:* Integrate muse in cards along with tag components ([6e9db84](6e9db8436a9631f85906dfaf8ce04f3de3e1e027))
- *comps:* Update navbar for muse and add navbar dropdowns with a11y fix for cards ([502b25c](502b25cd3c73f9ebfb49e13637606c6f2885e9cd))
- *core:* Switch to new color palette along with little refactorization ([75aaee8](75aaee89a2f27213516a5da9635cd50ed5d363eb))
- *core:* Add muse default color config to global variables ([b76da40](b76da406bad76586c0f108b592883f13c4030653))
- *core:* Optimize mizui grid system for lighter binary sizes ([a603141](a6031410fc5ac32b229df6635a240b435ff6ac2b))
- *core:* Update `padding` utilities for responsive viewports ([202cd44](202cd4401f33b3a62907380ac3940034e2e94032))
- *defaults:* Make shortened `font-family` variable names ([d1c015f](d1c015fce63aca7724c952324b66cccf6ab134ed))
- *mizui:* Update `font-family` vars with change in few things down the road ([69f039f](69f039f3b56af2a7ce7c27db742cb2c0e820ccf6))
- *prefabs:* Change to ordered headings of hero class in jumbo ([9879d65](9879d65f2c82a0838d296e85d5bbfe50602a0a7c))

### Refactoring Updates

- *app:* Delete app directory in favor of app specific gitmodules ([fc81664](fc8166454402b35bd5d6798f0c0b94536ed1fca0))
- *comps:* Refactor comps in favor of global vars with addition of close button ([2c6764d](2c6764d79365a6608d8208fbe002871fcfc67a66))

<!-- CHANGELOG SPLIT MARKER -->
