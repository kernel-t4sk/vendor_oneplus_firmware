# OnePlus Ace 2 (`udon` / `22803`) Prebuilt Firmware

- Source OTA: `StockROM/ColorOS-16.0.5-1301.zip` (`PHK110_11.H.59_3590_202611030133`, `security_patch=2026-11-01`)
- Note: `*.img` (notably `modem.img` at 272 MiB > GitHub 100 MB limit) is tracked via **Git LFS**.
  Make sure `git lfs pull` (or `lfs="true"` in repo manifest) is enabled before building.

| Partition | File | Size (B) | SHA1 | SHA256 |
|---|---|---|---|---|
| `abl` | `udon/radio/abl.img` | 221184 | `b436ec0a6279cd9875c381b843ee64ca487670ed` | `fdc0f850e72ca4cb3832db215dc4df81cac53ce77d6232fa362b562d31e249b2` |
| `aop_config` | `udon/radio/aop_config.img` | 16384 | `f99829c1adfef29c13716487516dd0da2c11c90c` | `2c6a8d52423bda1291f460881f415004713350dd1c2346960e0e5d52a057ebdb` |
| `aop` | `udon/radio/aop.img` | 237568 | `db090edfac183ac400eb0bfeeccd258a5f8ae222` | `aa532fcf8e31163bd7ce3031fc861ecc393fd6274189e92b40d328b90210774a` |
| `bluetooth` | `udon/radio/bluetooth.img` | 2093056 | `8c4502fd39b7eeb3c8e449dd98bca4e53446dc19` | `5a6f7e893c1133e2bc4efe7028b2f3213e0724d65adf60537a617b563d5085ec` |
| `cpucp` | `udon/radio/cpucp.img` | 159744 | `c2023a26ba11a7511d440b8fc470228d8abe7039` | `359c7a25fb826103cc3bede2b58c966ae01cd8f019d0b71cac507c7b11e4894e` |
| `devcfg` | `udon/radio/devcfg.img` | 57344 | `425e5b515dddb68847d1886980bb4077987c3f63` | `a0c7f738824f8eb125ae8ab1e4d197b25063ab25cef8b9c23da61f8954ed7357` |
| `dsp` | `udon/radio/dsp.img` | 67108864 | `ed6ae336f367d764dc24e10f3157e76efe6a5a81` | `e8370eb27e439b07828ce701afbd75e91923db0fddd044225e210f290ab1db30` |
| `engineering_cdt` | `udon/radio/engineering_cdt.img` | 1048576 | `e1265fc901542e77abd54a5342c66c79028a30da` | `d110c07381211f90ee45b67783deccfe3506386ec5cca4d371b0550a9739463e` |
| `featenabler` | `udon/radio/featenabler.img` | 98304 | `25059d1c31d2d37813b9a9c72d9d6ecb22f61e77` | `f0e365fda6fbaba8fa0ba3f51163feac4e772124cfef646ae5cc3b2639822bbd` |
| `hyp` | `udon/radio/hyp.img` | 1388544 | `15a852fe1efd8e0f4226dbab203e20172843b63f` | `19be0b5743aadca4a7dd31fa3b29ff67c411030d4e1073b64ff224a7c55551d5` |
| `imagefv` | `udon/radio/imagefv.img` | 106496 | `9b70ef3ff778bb8200b6d540cb922fefedc849e7` | `4d42b8acc56dd6801c8e33a5b8b215f49203e6dce4872adc086230f31ef1ccaa` |
| `keymaster` | `udon/radio/keymaster.img` | 368640 | `98ec7699f62788058891bf9f12242a53676caee7` | `e042f602fa42380aaa55d45c08c8729f21a0306003be21fb95a2c3e931ac1ee8` |
| `modem` | `udon/radio/modem.img` | 284725248 | `b6fc2d11a64644303a1d118cd3534b5da61b1576` | `3f266212df9cd385ff8d7b612bcbdddc7d0d3ba23ab15f08bac87e818e9d83bf` |
| `oplus_sec` | `udon/radio/oplus_sec.img` | 352256 | `45c2d35ee21db5d0439702112665a12306216285` | `5d1484d4f19ebda9a6a27dcdf7a2e20d86bd7b935c90c44c97a0aa6b70a71b18` |
| `oplusstanvbk` | `udon/radio/oplusstanvbk.img` | 774144 | `717134682bc4b109a97555e48f718fc7d05aea25` | `29c79ff30162bcfb89062129146592705e3735118b99d22bc030c88acd554985` |
| `qupfw` | `udon/radio/qupfw.img` | 53248 | `2668c1bb720b8d27271d7777dc11b1fe7a028d49` | `3e8e13f2aef13556c851907acbb5238437e0743853b23a7892f5b3848ec742f0` |
| `shrm` | `udon/radio/shrm.img` | 65536 | `fe052688808ba812b349e01ecbc09a3eea9c5d5c` | `9cc4fec2f2d753ee3b24c89353db28649751ddc1fbeb3ea2192f276840462238` |
| `splash` | `udon/radio/splash.img` | 15544320 | `cb2e25703010237a511ae8172b14ae5c516254ab` | `02a152304e6e9ce5b96d45a6f84e5a3ac01a469ff9c9d6e7086b22ed3f50c54c` |
| `tz` | `udon/radio/tz.img` | 3809280 | `138b09b01aa23ef7fb2b84579c5c9387d3ca9db0` | `cc5baff7c3b83120ca6134693e3b6083764126b86cf6c99361da1819d323be15` |
| `uefi` | `udon/radio/uefi.img` | 3153920 | `938a4aaf2dd31c50bc8563cd6a75119f5825dc12` | `a356a49956fba03dd381a381c8124bd47299d4ba95c82f1d49209f9e21dd7a86` |
| `uefisecapp` | `udon/radio/uefisecapp.img` | 172032 | `9833ac557b9f270c546efd618675e31894ee70b7` | `9053cdc8104ce5e75623e9e2b9f8b126aab0830acf8bd08ddcb8fbd3ee735dcd` |
| `xbl_config` | `udon/radio/xbl_config.img` | 118784 | `13901104d9a0a945e772c435fadb1044a187ee3e` | `c392e448435114eb155382da004d8eb984b71b5054ce2ef4eeddd1c92ff77ab0` |
| `xbl` | `udon/radio/xbl.img` | 1089536 | `62ede05b9c772b633057e3027ca2672afdfadce3` | `b32a31a62dd5f568ce19a2c5781e3027b0d71cb55e33ac4227424c1289dba304` |
| `xbl_ramdump` | `udon/radio/xbl_ramdump.img` | 843776 | `6a2b89c299a2e475bf97bd051f4de5d767c29379` | `d7f01482d5b2864ecfbf2bb788d2953cc7d79b6eb0f5a6f0162ca8e06b014615` |
