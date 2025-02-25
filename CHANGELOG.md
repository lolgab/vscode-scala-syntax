## Scala Syntax (official) Changelog

### 0.5.5 (2021/11/08 13:44 +00:00)
- [f1448ec](https://github.com/scala/vscode-scala-syntax/commit/f1448ecfee2c9a87c9644a1c2001f1111f1bfcb3) Add regex for interpolator identifier (@nicolasstucki)
- [f776810](https://github.com/scala/vscode-scala-syntax/commit/f776810b8a9a2d1fb0fa593d892aa7c3a0699165) Bump ansi-regex from 5.0.0 to 5.0.1 (@dependabot[bot])
- [57d2e61](https://github.com/scala/vscode-scala-syntax/commit/57d2e612ce59bbf5c62771aab235ccb9c43166cb) Bump nth-check from 2.0.0 to 2.0.1 (@dependabot[bot])
- [f9ea511](https://github.com/scala/vscode-scala-syntax/commit/f9ea511f74ad0d9d7f509bc12753bcc7dd2aec96) Handle names ending with symbolic characters (@nicolasstucki)
- [0e4f065](https://github.com/scala/vscode-scala-syntax/commit/0e4f065f92b0041c1d8970052279c7a0feb37a71) Fix `yarn install` (@nicolasstucki)
- [ab08f0a](https://github.com/scala/vscode-scala-syntax/commit/ab08f0aae2ebd352ecce4c90fe634dea1122f519) Bump path-parse from 1.0.6 to 1.0.7 (@dependabot[bot])
- [d050bd2](https://github.com/scala/vscode-scala-syntax/commit/d050bd27ad897ee0bdbe378630576c7a2b53f2f5) Uncomment CI push of generated files (@MaximeKjaer)
- [1434962](https://github.com/scala/vscode-scala-syntax/commit/1434962fa06bb1f7f6bd487f9768180d76e81366) Add missing changelog since 0.5.0 (@MaximeKjaer)
- [e054f5b](https://github.com/scala/vscode-scala-syntax/commit/e054f5bcdffbe2b1f968f7c64535021f876cd4b7) Fix GitHub Releases deployment command (@MaximeKjaer)

### 0.5.4 (2021/07/13 17:17 +00:00)
- [a50181b](https://github.com/scala/vscode-scala-syntax/commit/a50181bfe2f94f457096e2a5c854aefa88d3aa6a) Add auth token to github-changes command (@MaximeKjaer)
- [367c2a2](https://github.com/scala/vscode-scala-syntax/commit/367c2a2fc0ef92027bba49ff5711220e2f7a346d) Remove extensionKind so that other extensions can depend on scala-syntax via SSH/WSL2 (@tgodzik)
- [78f14d0](https://github.com/scala/vscode-scala-syntax/commit/78f14d02dd612f0d309fe64e9381dc4e16f1784d) upgrade vsce to 1.93.0 (@SethTisue)
- [ddf1c89](https://github.com/scala/vscode-scala-syntax/commit/ddf1c89abc9a05294637ea454f3f173a6fc76e97) upgrade github-changes to 2.0.2 (was 1.1.1) (@SethTisue)
- [11704e7](https://github.com/scala/vscode-scala-syntax/commit/11704e73a4ecdbce41f06f012450b868d9546d9a) Bump hosted-git-info from 2.8.8 to 2.8.9 (@dependabot[bot])

### 0.5.3 (2021/04/14 12:51 +00:00)
- [263c776](https://github.com/scala/vscode-scala-syntax/commit/263c77649af5e9097e87acb117def4627c088e7d) Update release branch to `main` (@nicolasstucki)
- [3caa8b6](https://github.com/scala/vscode-scala-syntax/commit/3caa8b60d405278f46f30aca3ed74ce1613ee6e6) Add support for web extension (@nicolasstucki)
- [e72b4c9](https://github.com/scala/vscode-scala-syntax/commit/e72b4c95debc2c38e509a7e9ee360de69245e8dd) Improve highlighting strategy for illegal $ (@nicolasstucki)
- [b28000b](https://github.com/scala/vscode-scala-syntax/commit/b28000b2aee00fb38f970cf21a3731739a26f041) Highlight illegal $ as end of string (@nicolasstucki)
- [6d3de7b](https://github.com/scala/vscode-scala-syntax/commit/6d3de7b28da85cd820f36965fc95115c290b7467) Identify illegal $ tokens in string interpolators (@nicolasstucki)

### 0.5.2 (2021/01/29 12:41 +00:00)
- [e179337](https://github.com/scala/vscode-scala-syntax/commit/e1793378bc49b4dc3eb5fa366b7d687b0cd64455) Fix broken regex (@MaximeKjaer)
- [78dc465](https://github.com/scala/vscode-scala-syntax/commit/78dc4656fb27a44f086e004036e82ab042f05d26) Fix 'end val' and  'end var' (@MaximeKjaer)
- [259b2da](https://github.com/scala/vscode-scala-syntax/commit/259b2dadbb256e30ff045305afaf866524ea16fb) Fix imports of packages or members with names starting with given (@MaximeKjaer)

### 0.5.1 (2021/01/20 14:13 +00:00)
- [a5806a4](https://github.com/scala/vscode-scala-syntax/commit/a5806a485d9d076589027df9af4f09046533b0c1) Pin github-changes version (@MaximeKjaer)
- [1bcf8af](https://github.com/scala/vscode-scala-syntax/commit/1bcf8af279f6074824beb4320c8351824a52f109) Identify bounds of `&&`, `||` and `!` operators (@nicolasstucki)
- [f8dcd02](https://github.com/scala/vscode-scala-syntax/commit/f8dcd026397e0eb967e52a5b37012118b53372a2) Simplify 'using' regex (@nicolasstucki)
- [3bbb8bd](https://github.com/scala/vscode-scala-syntax/commit/3bbb8bd2a684902ee5f19cacd8da97b9d2080062) Fix comments (@nicolasstucki)
- [e9a6ed5](https://github.com/scala/vscode-scala-syntax/commit/e9a6ed5760fc2e0b2061189ab2f63fb69de413fd) Properly highlight escape characters in `raw` interpolator (@nicolasstucki)
- [e1277fd](https://github.com/scala/vscode-scala-syntax/commit/e1277fdbac906f24e18ded7be9a736cb508c7d26) Capture `using` followed by quote splice (@nicolasstucki)

### 0.5.0 (2020/12/17 14:07 +00:00)
- [8c31186](https://github.com/scala/vscode-scala-syntax/commit/8c311862e55ed103ce6c6f5c5d3accc196903013) Disable deploy `Commit generated files` (@nicolasstucki)
- [6e93417](https://github.com/scala/vscode-scala-syntax/commit/6e9341733417928948f0e242f175cd85043ae5e6) Release 0.5.0
- [480fe19](https://github.com/scala/vscode-scala-syntax/commit/480fe19d674562d8e505f22588f64946f4b70154) Add yarn clean command (@MaximeKjaer)
- [be95818](https://github.com/scala/vscode-scala-syntax/commit/be958188508ce5de6411117eab961b5dba4cd24c) Identify quotes/splices start as the start of a normal block (@nicolasstucki)
- [9057516](https://github.com/scala/vscode-scala-syntax/commit/90575168381a866cd2e9c9e6c4c7e4a75e1c05e4) Migrate deployments to GitHub Actions (@MaximeKjaer)
- [08a35be](https://github.com/scala/vscode-scala-syntax/commit/08a35be22ce84114a9053a35e8c169671c254544) Improve detection of definitions (@nicolasstucki)
- [27c7da0](https://github.com/scala/vscode-scala-syntax/commit/27c7da0028f652556e5c0bf52228e95033399d0b) Highlight correctly multiple variable statement (@camilaagw)
- [5a57716](https://github.com/scala/vscode-scala-syntax/commit/5a57716c50ab9aa31ebb904b9cc42f4578161592) Add Node.js module caching to GitHub Actions (@MaximeKjaer)
- [9e9d91a](https://github.com/scala/vscode-scala-syntax/commit/9e9d91a3c07aad0f28be4d567ee2834c3b8f76c9) Fix extension build warnings (@MaximeKjaer)
- [456edd8](https://github.com/scala/vscode-scala-syntax/commit/456edd8bd001ea356d7a56001931d499b3dc5197) Add Scala CLA (@camilaagw)
- [feb6301](https://github.com/scala/vscode-scala-syntax/commit/feb6301cb08eb54b8dce44600543f0ac8dad525e) Fix #163: Update to new given syntax (@nicolasstucki)
- [5885a19](https://github.com/scala/vscode-scala-syntax/commit/5885a1984eb9020da02012ec9dd1fe1e4a39a84b) Highlight all soft modifiers (@camilaagw)
- [7445ae8](https://github.com/scala/vscode-scala-syntax/commit/7445ae86709d06d22972e04d109dbbb0d9d9f37a) Update README.md (@nicolasstucki)
- [de391d9](https://github.com/scala/vscode-scala-syntax/commit/de391d97ae9945790af775806e54c0219705b2cf) Fix typo in workflow name (@camilaagw)
- [a838344](https://github.com/scala/vscode-scala-syntax/commit/a83834480e9d6716dbdbb7427a719d98dbbf5b3a) Remove `as` syntax (@camilaagw)
- [0d09d80](https://github.com/scala/vscode-scala-syntax/commit/0d09d80b538136a8e4a5a9c465876166ef50caae) Add GitHub Actions badge (@nicolasstucki)
- [157b0ce](https://github.com/scala/vscode-scala-syntax/commit/157b0ce596ef375da4e0147306be2c11def790ef) Add tests on Github actions (@camilaagw)
- [0080fe4](https://github.com/scala/vscode-scala-syntax/commit/0080fe44968e1cc2eb3d621916b095bf7de3fc62) Identify `extends`, `with` and `derives` at the end of a line (@nicolasstucki)
- [76605c1](https://github.com/scala/vscode-scala-syntax/commit/76605c1370cd69a998bd6bbb4cf18ad488eb1e78) Highlight `val` with upper case (@camilaagw)
- [a4513e2](https://github.com/scala/vscode-scala-syntax/commit/a4513e2ebe473d529c86925ab7f22bd84730dbbe) Update `given` syntax (@camilaagw)
- [b3d18b4](https://github.com/scala/vscode-scala-syntax/commit/b3d18b417cf9b0d6bd2763bd01b7162485a152ba) Update release notes for 0.4.5

### 0.4.5 (2020/10/07 15:00 +00:00)
- [70968ba](https://github.com/scala/vscode-scala-syntax/commit/70968ba481218ce1521d5f93bd97ecc289036a2f) Update release notes for 0.4.4

### 0.4.4 (2020/10/07 14:50 +00:00)
- [b2b6fc6](https://github.com/scala/vscode-scala-syntax/commit/b2b6fc60c270199dec704fe67041e26527efaf20) Fix #148: Add regression test (@nicolasstucki)
- [e0c824a](https://github.com/scala/vscode-scala-syntax/commit/e0c824aaddba4e492ca2f2ad616564293dbad3c1) Prioritize matching of inline parameters (@nicolasstucki)
- [806d9a7](https://github.com/scala/vscode-scala-syntax/commit/806d9a7ce07a64e3000a094c99181017b687ff80) Fix #133: Add missing boundary condition (@nicolasstucki)
- [d2d1f8a](https://github.com/scala/vscode-scala-syntax/commit/d2d1f8a7444bc3d7e8cca6f45ab5200a4bad3041) Update release notes for 0.4.3

### 0.4.3 (2020/09/11 07:09 +00:00)
- [c60cc06](https://github.com/scala/vscode-scala-syntax/commit/c60cc061907420c432b25d9d1bce3c82cc3dd3f7) Update Scala.tmLanguage.json (@nicolasstucki)
- [5b3c402](https://github.com/scala/vscode-scala-syntax/commit/5b3c402877fe38bfd975f2d48ecaf80a04008ad6) Fix #139: Add given as a possible inline definition (@nicolasstucki)
- [2dd5afd](https://github.com/scala/vscode-scala-syntax/commit/2dd5afda3318196dacbf8c0ee3a8b42a00d921e7) Fix #133: Highlight inline as a soft keyword (@nicolasstucki)
- [bd9c1d9](https://github.com/scala/vscode-scala-syntax/commit/bd9c1d9c93b740f2d1160c8db47ff450ba9a0aef) Fix #140: Identify nameless given declarations (@nicolasstucki)
- [7333f3e](https://github.com/scala/vscode-scala-syntax/commit/7333f3e07756375af07486abd579d7d93aa33beb) Update dependencies (@nicolasstucki)
- [1d27380](https://github.com/scala/vscode-scala-syntax/commit/1d27380817b6a39cf041771c34c73b4fecef23ab) Fix #141: Remove old `extension on` syntax (@nicolasstucki)
- [c8aecd9](https://github.com/scala/vscode-scala-syntax/commit/c8aecd9efb89778e3be363e23cb533d357861e06) Fix #135: Idnetify package names in extension clause (@nicolasstucki)
- [6fddb3b](https://github.com/scala/vscode-scala-syntax/commit/6fddb3baedb7cb0a043a22a8d82546c6bfe46402) Fix #75: Fix Travis CI deployments from branches other than master (@MaximeKjaer)
- [6675978](https://github.com/scala/vscode-scala-syntax/commit/6675978c12d0a0ef079221cf431b80468a8710e7) Update release notes for 0.4.2

### 0.4.2 (2020/07/21 17:27 +00:00)
- [23d7bfe](https://github.com/scala/vscode-scala-syntax/commit/23d7bfedeb9bfa3cad14970b61b9a2e9dff6c44b) Improve highlighting of names in given declarations (@nicolasstucki)
- [e79e1b5](https://github.com/scala/vscode-scala-syntax/commit/e79e1b513ba5ea9c8cc3f4e01841c25f51886d2e) Fix #75: Add Travis CI deployment to GitHub Releases (@MaximeKjaer)
- [ff079c5](https://github.com/scala/vscode-scala-syntax/commit/ff079c5a92ce2877179d8752e679b5e57247cbfc) Bump lodash from 4.17.15 to 4.17.19 (@dependabot[bot])
- [05364bb](https://github.com/scala/vscode-scala-syntax/commit/05364bbb0b4f27fa60a1a3a56d571e04ec06a31d) Add tests (@nicolasstucki)
- [fd36c91](https://github.com/scala/vscode-scala-syntax/commit/fd36c91b7a44793b9c71b6a902b66ee52c6b99f9) Fix test (@nicolasstucki)
- [5d46fc7](https://github.com/scala/vscode-scala-syntax/commit/5d46fc75268c5f3eaacb6a50c1ac0799e6f71467) Remove Ul/ul number formats (@nicolasstucki)
- [46b8880](https://github.com/scala/vscode-scala-syntax/commit/46b88803f93eead0531044912fe4424c74a885d1) Fix #128: Add missing boundary for numbers (@nicolasstucki)
- [8aad5cd](https://github.com/scala/vscode-scala-syntax/commit/8aad5cdc15aa74eacd42fbcffb67a7c2fe4ec7a1) Fix #124: Identify extended class names as identifiers (@nicolasstucki)
- [ccb8bbd](https://github.com/scala/vscode-scala-syntax/commit/ccb8bbd69b51f562ef44d718591521bceb8124dc) Fix #125: Highlight literals with dots and exponents (@MaximeKjaer)
- [ec37a5e](https://github.com/scala/vscode-scala-syntax/commit/ec37a5e745d4972e2fecb4626e19d0b70cffb4c2) Update release notes for 0.4.1

### 0.4.1 (2020/07/08 17:49 +00:00)
- [d9c31e1](https://github.com/scala/vscode-scala-syntax/commit/d9c31e121a13a6aadbadfbe6e6a2ecad94225bee) Update team (@nicolasstucki)
- [373c3ff](https://github.com/scala/vscode-scala-syntax/commit/373c3fff3de5ea5ec004e91a0d91f1e3d8b3080b) Fix #119: Detect when `using` is an identifier (@nicolasstucki)
- [55c670d](https://github.com/scala/vscode-scala-syntax/commit/55c670dc213bf358ed9082be944c2930a1331c8a) Identify `enum` as a declaration (@nicolasstucki)
- [9df316a](https://github.com/scala/vscode-scala-syntax/commit/9df316a5979f5134d2fdaf34a0c2925842017119) Fix #122: Detect new on its own and let the other rules match the name (@nicolasstucki)
- [e377b96](https://github.com/scala/vscode-scala-syntax/commit/e377b9606a01c7f92738571a65169f9fbebe7942) Update README.md (@nicolasstucki)
- [16d49e5](https://github.com/scala/vscode-scala-syntax/commit/16d49e515aa026321560f7564adf8ad2a7998a03) Fix #118: Detect start of anonymous `new` (@nicolasstucki)
- [03641e3](https://github.com/scala/vscode-scala-syntax/commit/03641e36169903e219979beffeb45640083a735f) Use `keyword.other.import` (@nicolasstucki)
- [84f96e1](https://github.com/scala/vscode-scala-syntax/commit/84f96e1660c42380437a31e0cc3561c07c1c7499) Move `as` pattern to `keywords` patterns (@nicolasstucki)
- [02fe701](https://github.com/scala/vscode-scala-syntax/commit/02fe701695b14e6b982628ae40731147e5141c2e) Improve rule for `given` declaration detecion (@nicolasstucki)
- [b6e47aa](https://github.com/scala/vscode-scala-syntax/commit/b6e47aa2a0d15f7d1bd53c826bf309eee9523ab9) Fix #103: Detect `as` (@nicolasstucki)
- [d751b0e](https://github.com/scala/vscode-scala-syntax/commit/d751b0e729472ee562cde672f2ff3cb82d3c6089) Fix extension build in release script (@MaximeKjaer)
- [c7d3c9d](https://github.com/scala/vscode-scala-syntax/commit/c7d3c9d701705cdee9185365659b7e009998fd5d) Fix contributing instructions for generated output (@MaximeKjaer)
- [28089f6](https://github.com/scala/vscode-scala-syntax/commit/28089f693b9b018a0944748eabaa8f8965022387) Remove unused tsc devDependency (@MaximeKjaer)
- [8ad52d0](https://github.com/scala/vscode-scala-syntax/commit/8ad52d0aa690ca52cfd5b49b0dfe48e38fe4e7bc) Add extension build script (@MaximeKjaer)
- [ba8ce0c](https://github.com/scala/vscode-scala-syntax/commit/ba8ce0ca828dc9285f5692d72d1fdb39aa5d8610) Replace JS test scripts by package scripts (@MaximeKjaer)
- [7a0825f](https://github.com/scala/vscode-scala-syntax/commit/7a0825f100e2ad68e891f941cee1bf346f2c2fb8) Support `end extension` (@nicolasstucki)
- [0da2784](https://github.com/scala/vscode-scala-syntax/commit/0da2784b27f4b64fd2cda192ae6e391a5bf45b94) Fix #110: Highlight class/object names in imports (@nicolasstucki)
- [6f21e57](https://github.com/scala/vscode-scala-syntax/commit/6f21e5775214f0db6ce31a3bb524bfe52f36950c) Update dependencies (@nicolasstucki)
- [269b658](https://github.com/scala/vscode-scala-syntax/commit/269b65831b7b109465002fe3a490af4980e5c1e1) Improve `end` highlighting for type declarations (@nicolasstucki)
- [b3d1825](https://github.com/scala/vscode-scala-syntax/commit/b3d1825145165e7cbdb04b63bd52f540367765c8) Fix #107: Identify highlighting of identifier after an `end` (@nicolasstucki)
- [5404b87](https://github.com/scala/vscode-scala-syntax/commit/5404b87377f6713ef9f78f55083e322cdaeeb362) Fix #104: Distinguish open declaration `:`
- [af1e15d](https://github.com/scala/vscode-scala-syntax/commit/af1e15de1cf8051b34cce5d45081ad45e364b626) Fix #105: Detect all combinations of dot in numeric literals (@nicolasstucki)
- [2e3629c](https://github.com/scala/vscode-scala-syntax/commit/2e3629cff1d158e24f2417494a0d428c06e7fc39) Update release notes for 0.4.0

### 0.4.0 (2020/06/29 18:14 +00:00)
- [7f2f3f3](https://github.com/scala/vscode-scala-syntax/commit/7f2f3f34eaee47e3cd9d9004b374d49327359552) Regenerate Scala.tmLanguage.json (@nicolasstucki)
- [83acbc5](https://github.com/scala/vscode-scala-syntax/commit/83acbc5df6914b55d61b5967206cedf7bcea68cb) Use HTTPS (@nicolasstucki)
- [c445656](https://github.com/scala/vscode-scala-syntax/commit/c44565664193b37f063319c8c1d3466de5ba8c4b) Fix #84: Support with followed by a String literal (@nicolasstucki)
- [05a24a6](https://github.com/scala/vscode-scala-syntax/commit/05a24a615db6622ec99c5bccbf982d83b30728d4) Fix #68 and fix #77: End names on open brackets (@nicolasstucki)
- [2d32992](https://github.com/scala/vscode-scala-syntax/commit/2d32992549f191b0e4cf0a6f5efa5f831021c3d1) Support `extension on` (@nicolasstucki)
- [2f73059](https://github.com/scala/vscode-scala-syntax/commit/2f73059f67a6019343e3d966ac22ea43c0f64fb5) Support literals with underscores (@nicolasstucki)
- [0690707](https://github.com/scala/vscode-scala-syntax/commit/06907075c55d274aa114f1e30094e91c7ee3ad34) Support `extension` clause (@nicolasstucki)
- [81980d2](https://github.com/scala/vscode-scala-syntax/commit/81980d29fe1619a6d1935eda264f0406295a030d) Update README.md (@nicolasstucki)
- [3400412](https://github.com/scala/vscode-scala-syntax/commit/3400412da6a6b67191b3d473262c7e9058b85510) Fix #69: Do not use type definitions to highlight `.type` (@nicolasstucki)
- [280eeb2](https://github.com/scala/vscode-scala-syntax/commit/280eeb222c6147b74286f5a6a5a4f47bc05f364d) Update readme (@nicolasstucki)
- [059c9f4](https://github.com/scala/vscode-scala-syntax/commit/059c9f4817c8731455a717d5763db92ac8ab7524) Improve given imports (@nicolasstucki)
- [a67d959](https://github.com/scala/vscode-scala-syntax/commit/a67d95954f5e597190a0174c9e9275da1798eb74) Support `export` (@nicolasstucki)
- [cb5960e](https://github.com/scala/vscode-scala-syntax/commit/cb5960e6782a39c5258c867ce7eceecf93fce0ad) Fix #91: Support open classes (@nicolasstucki)
- [fb1cfbf](https://github.com/scala/vscode-scala-syntax/commit/fb1cfbfd3741bf348d0e6adac19f0395c5c8cd4f) Support `using` soft keyword (@nicolasstucki)
- [92832c8](https://github.com/scala/vscode-scala-syntax/commit/92832c87d844419691983639dcc1cd4b80021d2f) Fix #83: Match function extensions with (?=\\([^\\)]+=>) (@nicolasstucki)
- [e707aec](https://github.com/scala/vscode-scala-syntax/commit/e707aec9c9d6c2a456094a9e2772bb924075a9d2) Fix #83: Accept `extends` followed by a `(` (@nicolasstucki)
- [7e4af19](https://github.com/scala/vscode-scala-syntax/commit/7e4af19ac963017d7f8197630c2b699d5c2c36b3) Revert "Fix #75: Publish vsix files on release" (@nicolasstucki)
- [aa844fd](https://github.com/scala/vscode-scala-syntax/commit/aa844fd0486d4a7620b6b97e08c6a4e3308660d2) Revert "Fix #79: Fix travis.yml syntax" (@nicolasstucki)
- [4063ad8](https://github.com/scala/vscode-scala-syntax/commit/4063ad86f9da9fbc961e17967d21e3910da56da5) Fix #79: Fix travis.yml syntax (@nicolasstucki)
- [4231965](https://github.com/scala/vscode-scala-syntax/commit/4231965c6db95abd0cfffa8879968417acf6f5c6) Add badge (@nicolasstucki)
- [365c422](https://github.com/scala/vscode-scala-syntax/commit/365c422891d37e8f534129594c60375599b3fc0e) Fix #75: Publish vsix files on release (@anatoliykmetyuk)
- [f2ee8cc](https://github.com/scala/vscode-scala-syntax/commit/f2ee8cca5f2cfda940260a5f762daac6e528a6dc) Update release notes for 0.3.9

### 0.3.9 (2020/01/27 06:40 +00:00)
- [9a3fb4f](https://github.com/scala/vscode-scala-syntax/commit/9a3fb4fb689b256e4c4b10a56dfb15237f158836) Update .gitignore (@kiendang)
- [1906813](https://github.com/scala/vscode-scala-syntax/commit/19068130bf87eb0aec38ec286217b43ae85fdf8c) Update string interpolation highlighting (@kiendang)
- [9553c6e](https://github.com/scala/vscode-scala-syntax/commit/9553c6e6518c2802f6b96594963cacea6c622087) Remove $ as possible character in simple interpolated variable name (@kiendang)
- [c00e6ae](https://github.com/scala/vscode-scala-syntax/commit/c00e6ae26ea0cf4ebad0f03802b02231f394134a) Fix string interpolation with curly braces (@kiendang)
- [861d285](https://github.com/scala/vscode-scala-syntax/commit/861d2853f92753ef511df90c3ff21331c7e8781b) Remove `erased` keyword (@nicolasstucki)
- [d83ed44](https://github.com/scala/vscode-scala-syntax/commit/d83ed44b7c3d3578d625a0e51c693984e461735c) Revert "Revert "Fix #45: Use npx to execute github-changes"" (@nicolasstucki)
- [d4c7de5](https://github.com/scala/vscode-scala-syntax/commit/d4c7de53edae929bd05deefdf115aaa47ae02b77) Update release notes for 0.3.8

### 0.3.8 (2019/10/07 07:40 +00:00)
- [14d22e4](https://github.com/scala/vscode-scala-syntax/commit/14d22e4f897b611266c1ba726473ecc31f0665cb) Revert "Fix #45: Use npx to execute github-changes" (@nicolasstucki)
- [8f1deeb](https://github.com/scala/vscode-scala-syntax/commit/8f1deeb58ed8fa2d64bac7cc9a54d8bfbb14c49d) Update release notes for 0.3.7

### 0.3.7 (2019/10/07 07:20 +00:00)
- [a34b4d4](https://github.com/scala/vscode-scala-syntax/commit/a34b4d4d96c8e8ea4cf729bfac4fe15ab7cb74bb) Fix #62: Do not tag some classes as storage keywords (@nicolasstucki)
- [25af05a](https://github.com/scala/vscode-scala-syntax/commit/25af05af5c5c9ce079dfa9da8af7deb7f7063f02) Fix #51: Support vals with multi-assignment (@nicolasstucki)
- [6aa481b](https://github.com/scala/vscode-scala-syntax/commit/6aa481b435dd0fbb27d1c2e323cc3013d2ba3046) Update release notes for 0.3.6

### 0.3.6 (2019/09/23 11:04 +00:00)
- [a3d8f36](https://github.com/scala/vscode-scala-syntax/commit/a3d8f36947f8d582f451ff56f8637bc7dcbb14bc) Stop illegal char after end of line (@nicolasstucki)
- [aaa8332](https://github.com/scala/vscode-scala-syntax/commit/aaa833286c239c06dce74b33ea2a03efdc60b24f) Fix #45: Use npx to execute github-changes (@nicolasstucki)
- [643cbc3](https://github.com/scala/vscode-scala-syntax/commit/643cbc3156b3ef0ee19ab68345104a6fbc4ff814) Fix #57: Fix handling of scala.quoted opening quotes (@nicolasstucki)
- [666c463](https://github.com/scala/vscode-scala-syntax/commit/666c4637fcbf246154d2d334f247358d8fc7dcac) Fix #55: Add given imports syntax (@nicolasstucki)
- [505de8e](https://github.com/scala/vscode-scala-syntax/commit/505de8eb333f9b4399904067807dadeaded3a5e2) Update release notes for 0.3.5

### 0.3.5 (2019/09/17 13:38 +00:00)
- [d0b9bbd](https://github.com/scala/vscode-scala-syntax/commit/d0b9bbd010a302a4429b8432c50cdcb26515d833) Remove outdated `as` (Dotty syntax) (@nicolasstucki)
- [195db9e](https://github.com/scala/vscode-scala-syntax/commit/195db9e5e0dddc9c771b91e7d1f4770dcc3595ca) Update version to 0.3.5 (@nicolasstucki)
- [71ba0d8](https://github.com/scala/vscode-scala-syntax/commit/71ba0d86b333182edf1c8dd4556b1a7d8a132910) Fix homepage (@nicolasstucki)
- [6525f7d](https://github.com/scala/vscode-scala-syntax/commit/6525f7d949401310d62402a4f8b0978e8c961489) Fix #47: Support `then` keyword and `end` soft keyword (@nicolasstucki)
- [b9b645a](https://github.com/scala/vscode-scala-syntax/commit/b9b645a99469d68ed45a20bb0fec76e17619e3d1) Make `inline`, `opaque`, `as` and `derives` soft keywords (@nicolasstucki)
- [59908f2](https://github.com/scala/vscode-scala-syntax/commit/59908f2b7e17946477995e6b907442e72f45320e) Security updates (@nicolasstucki)
- [294e24e](https://github.com/scala/vscode-scala-syntax/commit/294e24e77b3c1c5910bce938a4b2c3d3d6e3f2c0) Add missing keywords from Dotty 0.17.0-RC1 (@nicolasstucki)
- [f3d587d](https://github.com/scala/vscode-scala-syntax/commit/f3d587d75ac8ca92c006ff72a76c8a4a0158ed76) Update release notes for 0.3.4

### 0.3.4 (2019/06/30 16:26 +00:00)
- [b3bbdf0](https://github.com/scala/vscode-scala-syntax/commit/b3bbdf0e7dfad0cecdf9166ff38ddd4f3bae0143) Fix opening paren matches with closing paren in character literal (@PanAeon)
- [eef0470](https://github.com/scala/vscode-scala-syntax/commit/eef04706197f3c972de087eeaa4cd7536c9b2a99) Fix bug with // inside of a block comment (@PanAeon)
- [6c49b5e](https://github.com/scala/vscode-scala-syntax/commit/6c49b5eb2e3342b785cdec94114e83a73105f6e5) Update release notes for 0.3.3

### 0.3.3 (2019/06/25 12:55 +00:00)
- [f50e487](https://github.com/scala/vscode-scala-syntax/commit/f50e487e8cdce9b41b0d33f8e9949764c08b0e5d) Add top level rule for identifiers inside the backticks (@PanAeon)
- [c84000f](https://github.com/scala/vscode-scala-syntax/commit/c84000fbfa1c70e91011d4aff90c7222fe96d73a) Welcome PanAeon to the team! (@olafurpg)
- [be15605](https://github.com/scala/vscode-scala-syntax/commit/be15605de49de729a0c6760cd17f9184fbb43892) Commiting missing changes (@PanAeon)
- [6fecc7d](https://github.com/scala/vscode-scala-syntax/commit/6fecc7d08d4f79faf904467dd840a4e4e89b4620) Fix nested comments, make links highlighted in the scaladoc, add @constructor keyword, remove dead code, add snap tests for comments. (@PanAeon)
- [0be6724](https://github.com/scala/vscode-scala-syntax/commit/0be6724d87303aeed41f6aa9dac07283cf9b92d4) Fix nested character classes. Remove $schema field. Remove redundant 'special-identifier' rule. (@PanAeon)
- [7affc4e](https://github.com/scala/vscode-scala-syntax/commit/7affc4ed719a3760db745958f83aa744405e1e55) this repo powers highlighting on GitHub (@SethTisue)
- [53610fa](https://github.com/scala/vscode-scala-syntax/commit/53610fa130166351c1c1545798c453a9860e2f0d) Update release notes for v0.3.2

### v0.3.2 (2019/05/28 07:13 +00:00)
- [86f3239](https://github.com/scala/vscode-scala-syntax/commit/86f32392e9b8584bc7afe60d4f9d2fe7df8fc15d) fix #5 broken ids with unicode characters. Updated identifiers regexes for val,def,import,parameter-list,package,type. Minor clean up. Added unit test for unicode (@PanAeon)
- [2d16efe](https://github.com/scala/vscode-scala-syntax/commit/2d16efef91f3d5a8751e9b89b76e4803cea1e163) fix #10 broken single quote symbol. add .metals to .gitignore (@PanAeon)
- [93a7147](https://github.com/scala/vscode-scala-syntax/commit/93a7147f043259e6ea9d4757c9ff25fd0e7fe437) update vscode-tmgrammar-test to 0.0.5.'snap' file format change (@PanAeon)
- [fa35d48](https://github.com/scala/vscode-scala-syntax/commit/fa35d48e1e90ee81071c2ddd44cb0067a33d728b) add test step to travis (@PanAeon)
- [aecb9c3](https://github.com/scala/vscode-scala-syntax/commit/aecb9c3bfe9cf57701ab8370215f69a5af328e25) Add snapshot test with various examples from scala spec (@PanAeon)
- [4bde54b](https://github.com/scala/vscode-scala-syntax/commit/4bde54bc67a42ccff5cc0a94d34108a2623b0c2d) Add vscode-tmgrammar-test module, include tests in ci, add unit and snapshot tests for lexical constructs (@PanAeon)
- [7ff15a6](https://github.com/scala/vscode-scala-syntax/commit/7ff15a6e2053bd55a424fb24b60db32a0dc26fc3) Update release notes for v0.3.1

### v0.3.1 (2019/05/14 09:22 +00:00)
- [6453d96](https://github.com/scala/vscode-scala-syntax/commit/6453d9636fc8558b4e2ac1f933d252853d2fda97) Review fixes, add missing scope to the interpolated string's quotes (@PanAeon)
- [a4fb9a0](https://github.com/scala/vscode-scala-syntax/commit/a4fb9a0c33ca337b0833bbbf40213a9f0a593891) generalize string interpolation to processed strings, i.e. <id>"..." (@PanAeon)
- [e007203](https://github.com/scala/vscode-scala-syntax/commit/e00720354213fe6ad67ae4e5887758c38cbc684d) string interpolation - correct variable name to match sem. meaning, don't mark $vars as vars to be more consistent with the ${var.other} (@PanAeon)
- [925245c](https://github.com/scala/vscode-scala-syntax/commit/925245c1eaeb712987256d2a45398bed6d155749) Add string interpolation highlighting (@PanAeon)
- [5b536a4](https://github.com/scala/vscode-scala-syntax/commit/5b536a4c1e3b46fd0a8dc22ff48c362eb0da0158) Commit auto-generated tmLanguage.json (@olafurpg)
- [d28c383](https://github.com/scala/vscode-scala-syntax/commit/d28c3832d6ddefb2f3e3a931f75f82a87ad761a6) Update release notes for v0.3.0

### v0.3.0 (2019/05/02 13:52 +00:00)
- [c995170](https://github.com/scala/vscode-scala-syntax/commit/c9951706d7032146b7c9ff4d88fe1dde6c244086) Add missing vsce dependency in package.json. (@olafurpg)
- [6246f55](https://github.com/scala/vscode-scala-syntax/commit/6246f550409b2e249a879accac49c878453e4d2c) Update release notes for v0.3.0
- [27b8cd5](https://github.com/scala/vscode-scala-syntax/commit/27b8cd570be9bcae775ca1b49cad8fc945b59fd1) Add missing vscode:publish command from package.json. (@olafurpg)
- [25c62bc](https://github.com/scala/vscode-scala-syntax/commit/25c62bccd70ee4cd077236e87d89646debd82515) Update release notes for v0.3.0
- [ba65f13](https://github.com/scala/vscode-scala-syntax/commit/ba65f1317dc728e3f5203bf78dadad67b6aa2734) Use SSH remote instead of HTTPS. (@olafurpg)
- [0546974](https://github.com/scala/vscode-scala-syntax/commit/0546974ba16b0b828dfa095aaed7d1a70331563e) Make ci-release.sh script executable (@olafurpg)
- [f302051](https://github.com/scala/vscode-scala-syntax/commit/f3020516ecaa80dbb9b74350ed01302c619165c6) Replace links from Metals to Scala Syntax (@olafurpg)
- [bc2fa54](https://github.com/scala/vscode-scala-syntax/commit/bc2fa542f39592cc6b204738b3bbe4e08ccfaaf2) Replace npx with ts-node for faster build script. (@olafurpg)
- [869e06b](https://github.com/scala/vscode-scala-syntax/commit/869e06bbfab7534758db59f41b5c978f523a3d75) Configure CI to release on tag push. (@olafurpg)
- [f554622](https://github.com/scala/vscode-scala-syntax/commit/f554622a468ee49316f509c3a6c7801c6f28fc8b) Remove snippet package, fixes #18 (@olafurpg)
- [c9a4a36](https://github.com/scala/vscode-scala-syntax/commit/c9a4a36253af5dd78dfecfa19c81fcac3f023674) Add pre-package check. Add proper build script. Updated .vscodeignore. Updated README. (@PanAeon)
- [f3aca62](https://github.com/scala/vscode-scala-syntax/commit/f3aca62801a0c3fa3faa24c30ad01bd9783e5634) Convert syntax file to Typescript, add utils to work with ts file, update docs (@PanAeon)
- [ebe1ad0](https://github.com/scala/vscode-scala-syntax/commit/ebe1ad0d9a6a2535aa3d1049c820a250d697da39) Add auto-closing pair for string interpolation (@hugo-vrijswijk)
- [2e5e24a](https://github.com/scala/vscode-scala-syntax/commit/2e5e24a61be430abf11eb4e3a4a5a65b7b8edd64) Fix case class/object highlighting (@Hydrotoast)
- [4ad7830](https://github.com/scala/vscode-scala-syntax/commit/4ad7830d41cd172ac2ef5a10a422fab8b8942230) Update publish info (@nicolasstucki)
- [71fc3fd](https://github.com/scala/vscode-scala-syntax/commit/71fc3fdd3bdcb93e9ebb856845f1e391df070153) Add scala syntax as snippet requirement (@gabro)
- [d275c5f](https://github.com/scala/vscode-scala-syntax/commit/d275c5f824c2184d1c52cd0bc0679f5d2788bfef) Split syntax and snippets (@gabro)
- [78ebbbe](https://github.com/scala/vscode-scala-syntax/commit/78ebbbe72f9f054ea7f6cb6d08100e90bd7c93ce) Enable extension on `.sc` files (@Duhemm)
- [19a2051](https://github.com/scala/vscode-scala-syntax/commit/19a2051e58d88b9bf320b9343746d547f8b9648a) Publish as scala-lang (@nicolasstucki)
- [829b8eb](https://github.com/scala/vscode-scala-syntax/commit/829b8ebbce658271d0421f58e9ee9f23e8f52a8a) Update version (@nicolasstucki)
- [aef901c](https://github.com/scala/vscode-scala-syntax/commit/aef901c015c994982294b511c6a83638edebfcfe) Update syntax (@nicolasstucki)
- [a68e1ad](https://github.com/scala/vscode-scala-syntax/commit/a68e1ad10be00f648eaa86b789884a358c30f3ab) Update version (@nicolasstucki)
- [e53ddad](https://github.com/scala/vscode-scala-syntax/commit/e53ddad3fa57e26516713d55937871e0b5af0afc) Add snippets (@nicolasstucki)
- [64aa83c](https://github.com/scala/vscode-scala-syntax/commit/64aa83c48622a50208ca4a3eeadec6b636469c36) Add references (@nicolasstucki)
- [49ec358](https://github.com/scala/vscode-scala-syntax/commit/49ec3584a2658209c24fa74a9da19d26a7b833ed) Update to 0.1.3 (@nicolasstucki)
- [ea80cb7](https://github.com/scala/vscode-scala-syntax/commit/ea80cb74ed611eed3b206316c5946f5ef9259904) Add some keywords (@nicolasstucki)
- [fa7fea7](https://github.com/scala/vscode-scala-syntax/commit/fa7fea79764cd295cbc25005bd5decbe954c9a59) Remove some snippets to keep options simple (@nicolasstucki)
- [27a8e69](https://github.com/scala/vscode-scala-syntax/commit/27a8e6939df0655e8e8f6ac99f1ce68efd549080) Update to 0.1.2 (@nicolasstucki)
- [63e4585](https://github.com/scala/vscode-scala-syntax/commit/63e45856f0f2a78f87813235cfa4e12d18a08bce) Add some basic code snippets (@nicolasstucki)
- [3ff361f](https://github.com/scala/vscode-scala-syntax/commit/3ff361f2cbb91fdca1ed90ff0928e67c1ab12b67) Update version to 0.1.1 (@nicolasstucki)
- [4821223](https://github.com/scala/vscode-scala-syntax/commit/48212238d9891908a0b0e5461e5acc6d53db3d4d) Fix closing brackets not being identified (@nicolasstucki)
- [b1d10d6](https://github.com/scala/vscode-scala-syntax/commit/b1d10d6267abe21fd8423411323b903ce5b74ff1) Add debbug launcher (@nicolasstucki)
- [a19c6c4](https://github.com/scala/vscode-scala-syntax/commit/a19c6c4b8b27f39276b1eef8c7ee2185e60d987e) Update version and publisher (@nicolasstucki)
- [1d9c36e](https://github.com/scala/vscode-scala-syntax/commit/1d9c36e747d3103930112895887f888bb189e8d2) Fix #1: Publish in market place (@nicolasstucki)
- [a95cf09](https://github.com/scala/vscode-scala-syntax/commit/a95cf090518e50db7c825c5baa1247afd6909383) Remove old ported comments (@nicolasstucki)
- [db11ec3](https://github.com/scala/vscode-scala-syntax/commit/db11ec3eb423751bd253dc6cac3dcd7adf61a410) Fix expression and type quotes (@nicolasstucki)
- [5518b86](https://github.com/scala/vscode-scala-syntax/commit/5518b86e30bf6e39dc60fb33950e7d74995115a3) Initial commit (@nicolasstucki)