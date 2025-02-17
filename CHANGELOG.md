# Changelog

<!--next-version-placeholder-->

## v2.4.4 (2023-04-16)
### Fix
* **export:** Handle fields for offline rendering ([`8b9920f`](https://github.com/Kitware/trame-vtk/commit/8b9920fdc7328d8fa20bd3d6c3d2566f1175d883))
* **ParaView:** Add missing widgets args in scene ([`47c4f0e`](https://github.com/Kitware/trame-vtk/commit/47c4f0efc3ad2feed4a12901a33e1442aab15b29))

### Documentation
* **pv:** Add paraview validation example ([`9146694`](https://github.com/Kitware/trame-vtk/commit/914669478cb2ba088131d8da81ddc287003afb23))

## v2.4.3 (2023-04-07)
### Fix
* **export:** Add export for VtkLocalView ([`b58ccf4`](https://github.com/Kitware/trame-vtk/commit/b58ccf4109b25f567cac0f8f1185ab71e00c14dc))

## v2.4.2 (2023-03-31)
### Fix
* **vue-vtk-js:** Bump version of vue-vtk-js ([`11c14b9`](https://github.com/Kitware/trame-vtk/commit/11c14b9b19a6fe1d8019c63c2d94806caf438954))
* **widgets:** Use proper order initialization ([`f3c0505`](https://github.com/Kitware/trame-vtk/commit/f3c05053a81786fc1627cd55f5a360b580c52a10))
* **VtkRemoteLocalView:** Add support for widgets ([`79d106a`](https://github.com/Kitware/trame-vtk/commit/79d106ac2ffb432517bef8f57d80551ff699466d))
* **behavior:** Implement handler for vtkOrientationMarkerWidget ([`01e035f`](https://github.com/Kitware/trame-vtk/commit/01e035ff6f8f3fd52717b627f6db57961f4debc1))
* **LocalView:** Add infrastructure to support behaviors ([`26e1945`](https://github.com/Kitware/trame-vtk/commit/26e194535c2e5ca910ebc053b16bd7abacd91cbe))

### Documentation
* **examples:** Simplify code ([`b9afcea`](https://github.com/Kitware/trame-vtk/commit/b9afceadd32a565aef380ec148a05d014e115687))
* **examples:** Add button toggles for widgets ([`ed307b3`](https://github.com/Kitware/trame-vtk/commit/ed307b32b888e9698e87f5f6af14b5f3cb2e4d8f))
* **examples:** Update the widget ones ([`cdda471`](https://github.com/Kitware/trame-vtk/commit/cdda471df5c2364e7359c2d6533ffcd4e4b38cf0))
* **examples:** Add pyvista axes widget examples ([`b1598f6`](https://github.com/Kitware/trame-vtk/commit/b1598f61c6a53d77acd5688026560069153e6886))

## v2.4.1 (2023-03-27)
### Fix
* **paraview:** Fix protocol ([`b72425c`](https://github.com/Kitware/trame-vtk/commit/b72425cdde30344b15cebf8dd1b11aa62701176f))

## v2.4.0 (2023-03-24)
### Feature
* **protocols:** Copy protocols from VTK exactly ([`9fe3c26`](https://github.com/Kitware/trame-vtk/commit/9fe3c261bc78a8814e1f4bab37ac6df3977144d8))

### Fix
* **messages:** Only print no serializer warning once per instance type ([`65db322`](https://github.com/Kitware/trame-vtk/commit/65db3229b9b0d15183a3fa882a825b4a9ea745ea))
* **logger:** Add environment variable for setting serializer log level ([`3c1614c`](https://github.com/Kitware/trame-vtk/commit/3c1614c82f47528e71de69916baa22961177c3d9))
* **paraview:** Update mouse wheel to match VTK version ([`6f93186`](https://github.com/Kitware/trame-vtk/commit/6f931867e3b63aa59e03799495ade03c59b31abf))
* **helper:** Update name to `_trame_server` ([`2b2b607`](https://github.com/Kitware/trame-vtk/commit/2b2b607da8abc3639b791c4411ffb22d9d3a147c))
* **vue-vtk-js:** Upgrade to prevent client error on unmount ([`3a2acee`](https://github.com/Kitware/trame-vtk/commit/3a2aceececd6f70e2bc4e78c309b051723eb9d45))
* **mouse_handler:** Only trigger animation registration on first "down" ([`88bac50`](https://github.com/Kitware/trame-vtk/commit/88bac500cbd3d6f3775a7cab9170c775a5683ff6))
* **mouse_handler:** Apply a couple of fixes to mouse wheel event ([`45505ef`](https://github.com/Kitware/trame-vtk/commit/45505ef25bb76a4d04bddd9cecdc375999de9e1b))
* **vue-vtk-js:** Update vue-vtk-js to the newest version ([`eb7310d`](https://github.com/Kitware/trame-vtk/commit/eb7310dd9e763b069de438ad33db3173965c2e81))

## v2.3.5 (2023-03-21)
### Fix
* Axes serializer ([`cc2136d`](https://github.com/Kitware/trame-vtk/commit/cc2136df0d4ff850f25f791ffc76f3ae2ba10a92))

## v2.3.4 (2023-03-10)
### Fix
* **RemoteView:** Support no size at startup ([`29c5587`](https://github.com/Kitware/trame-vtk/commit/29c5587f0ca72c78972d6304a48d469231d523e6))

## v2.3.3 (2023-03-10)
### Fix
* **RemoteView:** Initial still_ratio ([`130ff9a`](https://github.com/Kitware/trame-vtk/commit/130ff9a0c146e91ac2230f8cc81fc5eb468d6b73))

## v2.3.2 (2023-03-09)
### Fix
* **serializer:** Add support for LUT components ([`3ace3f5`](https://github.com/Kitware/trame-vtk/commit/3ace3f5ffa6e0af6d9db029e0a5ca6fb3f4a7174))

## v2.3.1 (2023-03-09)
### Fix
* **Serializer:** Properly handle LookupTable size ([`95cfd2d`](https://github.com/Kitware/trame-vtk/commit/95cfd2d196bb00e28648f698a63a219e553b54cf))

## v2.3.0 (2023-03-09)
### Feature
* **screenshot:** Allow screenshot extract ([`8db1f08`](https://github.com/Kitware/trame-vtk/commit/8db1f0845206fc65ec02f7169aa40ab63bb4d792))

### Fix
* **vue-vtk-js:** Update to 3.1 to get AxesActor + screenshot ([`cfe0b19`](https://github.com/Kitware/trame-vtk/commit/cfe0b19bd22f11ff061031dd2b1ac1980f837d8b))
* **LocalView:** Add support for vtkAxesActor ([`7d21817`](https://github.com/Kitware/trame-vtk/commit/7d21817e7a39f6168081584bf62c81139c6b99d9))

## v2.2.3 (2023-03-03)
### Fix
* **LocalView:** Allow view update ([`034c142`](https://github.com/Kitware/trame-vtk/commit/034c142c17987a28adf30c99b1c72258c8ce6e5b))

### Documentation
* **widget:** Simple plane/clip ([`bb95910`](https://github.com/Kitware/trame-vtk/commit/bb9591020966a889885e8a7816c8bd53cfb4a3fc))
* **widget:** Simple plane/clip ([`1365d51`](https://github.com/Kitware/trame-vtk/commit/1365d510ebffe0589e3579cbe6b25e8b349626cc))

## v2.2.2 (2023-02-28)
### Fix
* **widget:** Add a class to wrap vtkAbstractWidgets and make them easier to use ([`29e39d4`](https://github.com/Kitware/trame-vtk/commit/29e39d42b7115c6c1df82f7be38c7ecc456aedf5))

## v2.2.1 (2023-02-26)
### Fix
* **vue3:** Unify template generation ([`c13934e`](https://github.com/Kitware/trame-vtk/commit/c13934e20dc5815645ba7f20dd61f831b96d0cd2))

### Documentation
* **example:** Update latest vue3 syntax ([`5b64088`](https://github.com/Kitware/trame-vtk/commit/5b64088d05ad5b596758324204092404b8a33f00))

## v2.2.0 (2023-02-25)
### Feature
* **LocalRemote:** Allow full camera sync with helper method ([`a750af2`](https://github.com/Kitware/trame-vtk/commit/a750af248c5d7025491bca1a8ff6cd0a9bab441b))

### Fix
* **vue-vtk-js:** Update to latest version ([`672e887`](https://github.com/Kitware/trame-vtk/commit/672e88787c5a3c5cbc15b1858291c4131f2f1e50))

### Documentation
* **example:** Support toggle camera sync ([`fb9ab41`](https://github.com/Kitware/trame-vtk/commit/fb9ab41eaf7d9ee25eea3cae98ddab75c00e3611))

## v2.1.0 (2023-02-23)
### Feature
* **vue23:** Update client code to work with vue2/3 ([`7a8f546`](https://github.com/Kitware/trame-vtk/commit/7a8f546de013f61f7973118b992fec5889c35690))

### Fix
* **web:** Migrate JS into vue-vtk-js>=3 ([`9cd279a`](https://github.com/Kitware/trame-vtk/commit/9cd279a3dee3e88aeb0891f370eb65a6a1e3aa1c))

## v2.0.18 (2023-02-23)
### Fix
* **version:** Add __version__ ([`c9ab451`](https://github.com/Kitware/trame-vtk/commit/c9ab451d9e397f2a9c64b488d957915086a81ddc))

## v2.0.17 (2023-02-01)
### Fix
* **BigInt:** Add support for LocalView ([`aa34620`](https://github.com/Kitware/trame-vtk/commit/aa34620642c64ceb5fd625c83b22fc7f50e823ff))

## v2.0.16 (2023-01-27)
### Fix
* ImageData extent and vtkSmartVolumeMapper ([`fc096c0`](https://github.com/Kitware/trame-vtk/commit/fc096c0e0190bfef2127aef2f46e3aa9ccdd8893))

## v2.0.15 (2023-01-20)
### Fix
* **vtk:** Handle CubeAxes grid color + light + disable_auto_switch ([`d89c04e`](https://github.com/Kitware/trame-vtk/commit/d89c04e265a28234cd3467866c016247fc5d6e36))
* CubeAxesSerializer colors ([`3ea17a4`](https://github.com/Kitware/trame-vtk/commit/3ea17a44f431a0cf8afe4949e7d52c4d631eb4fb))

## v2.0.14 (2023-01-10)
### Fix
* Convert RGB colors to hex ([`0be279e`](https://github.com/Kitware/trame-vtk/commit/0be279e6190bcc7c54b9fc725da6df014376656a))

## v2.0.13 (2023-01-10)
### Fix
* **vue-vtk-js:** Bump version to 2.1.3 to support delta ([`8f1d569`](https://github.com/Kitware/trame-vtk/commit/8f1d569e3329ea2a8f7285e06d2083c932bcac10))
* **RemoteLocal:** Fix API call to use delta ([`781c282`](https://github.com/Kitware/trame-vtk/commit/781c282b1c812309b1f28ac7c24c69e0506628dd))

## v2.0.12 (2022-12-16)
### Fix
* **RemoteView:** Expose still_ratio/quality properties ([`7278d5e`](https://github.com/Kitware/trame-vtk/commit/7278d5ed7b8872167a9e9c653792b1b8543ac5ab))
* **LocalView:** Add push_camera ([`a9e4513`](https://github.com/Kitware/trame-vtk/commit/a9e4513e43fea443ee02d2de002270d666515913))

## v2.0.11 (2022-12-09)
### Fix
* **vue-vtk-js:** Update to 2.1.2 ([`3cf8913`](https://github.com/Kitware/trame-vtk/commit/3cf8913158e36496e564c4a544f07a2f2cf6c630))

## v2.0.10 (2022-12-04)
### Fix
* **LocalView:** Add multi-view + delta update handling ([`06b6a07`](https://github.com/Kitware/trame-vtk/commit/06b6a0713e91e92ed165f3ec71e4684b988c4d58))

### Documentation
* **example:** Fix flake8 issue ([`f80d982`](https://github.com/Kitware/trame-vtk/commit/f80d982011d5b1f9b7e60c1b3b38efba7cab6a80))
* **examples:** Add validation examples ([`209914a`](https://github.com/Kitware/trame-vtk/commit/209914ab142fe6bf2f7459a83c4f533d32157212))

## v2.0.9 (2022-11-05)
### Fix
* **LocalView:** Properly handle add/remove actor ([`85ee285`](https://github.com/Kitware/trame-vtk/commit/85ee285f67cf08438d37bae0bfd8d84ffe34db35))

## v2.0.8 (2022-10-20)
### Fix
* Improve VTK mapper and scalar bar serializers ([`fb94e81`](https://github.com/Kitware/trame-vtk/commit/fb94e81ef86c152f207e4fd442747c0d318a8dde))
* Improve VTK error reporting capabilities ([`58b71d3`](https://github.com/Kitware/trame-vtk/commit/58b71d330d0ba8e1afba2c3d3ef918d6090dc193))

## v2.0.7 (2022-10-05)
### Fix
* **VtkLocalView:** Automatically register update on_server_ready ([`5b5d296`](https://github.com/Kitware/trame-vtk/commit/5b5d296cc67518801c5ebff9397d55f99461c822))

## v2.0.6 (2022-09-01)
### Fix
* **VtkPiecewiseEditor:** Expose piecewise editor widget ([`1e44b6d`](https://github.com/Kitware/trame-vtk/commit/1e44b6d71f511d19dc95ee42e0d9c981258259b1))

### Documentation
* **coverage:** Remove codecov PR comment ([`5cce2fe`](https://github.com/Kitware/trame-vtk/commit/5cce2fe064625de02d6c590b65c925e31e0b36be))
* **coverage:** Add .coveragerc ([`6dd5e1d`](https://github.com/Kitware/trame-vtk/commit/6dd5e1d2ab44ff42ea5510db9aab736e49104b41))
* **ci:** Add coverage and codecov upload ([`b4d7c6e`](https://github.com/Kitware/trame-vtk/commit/b4d7c6ee53917e94ef0a9f5ae27db7cb8af430b6))
* **readme:** Add CI badge ([`214e1bf`](https://github.com/Kitware/trame-vtk/commit/214e1bfb4419a83c6390f1b8bf3cafa75fb3d1c7))
* **contributing:** Add CONTRIBUTING.rst ([`4bb579d`](https://github.com/Kitware/trame-vtk/commit/4bb579de9779b735f7517d5e47bff15dc6182066))

## v2.0.5 (2022-06-01)
### Fix
* **paraview:** Replace invalid import path ([`bd33f2a`](https://github.com/Kitware/trame-vtk/commit/bd33f2a2c71f80792a3039271d70b32f100aeed0))

## v2.0.4 (2022-05-31)
### Fix
* **widgets:** Expose more props ([`2fa0156`](https://github.com/Kitware/trame-vtk/commit/2fa01565461f62f96d3a18b2f649b5484981e5bf))

## v2.0.3 (2022-05-29)
### Fix
* **js:** Add trame-vtk.js before uploading to pypi ([`ec9b1f9`](https://github.com/Kitware/trame-vtk/commit/ec9b1f9e67f43618824459a2a7b6cfbf798dbf64))

## v2.0.2 (2022-05-27)
### Fix
* **paraview:** Remove unnecessary check for import ([`301b684`](https://github.com/Kitware/trame-vtk/commit/301b684378f30d46e93939da67ebd11f2027bf41))

## v2.0.1 (2022-05-27)
### Fix
* Add initial CI, including semantic release ([`2f72dda`](https://github.com/Kitware/trame-vtk/commit/2f72dda6bf851b8afea1f1cf34d616554b5b5dfc))
