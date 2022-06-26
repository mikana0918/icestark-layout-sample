# Description
This is a sample repository to demonstrate how to create layout app with icestark.  
Sccafolded with official layout template.  

see: https://micro-frontends.ice.work/docs/guide/use-layout/vue

## Child apps
- [mikana0918/icestark-vue2-child-sample](https://github.com/mikana0918/icestark-layout-sample)
  demonstrates how to setup Vue 2.X app with ice/stark-app.

## Package
| Key | Value |  
|---|---| 
| Vue.js | 3.2.16   |  
| Vite.js | 2.6.0   |  
| Vue Router  |  4.0.11 for Vue 3.x  |
| @ice/stark  |  2.6.1 for Microfrontend integration  |
| element-plus  |  1.2.0-beta.6 for UI  |

## Install
```bash
$ git clone https://github.com/mikana0918/icestark-layout-sample.git
$ cd icestark-layout-sample
$ yarn run dev
```

Now, you can go to http://localhost:3000/ .

## Run as microfrontend
Make sure you have setup locally this repository and [mikana0918/icestark-vue2-child-sample](https://github.com/mikana0918/icestark-layout-sample)

```bash
$ cd icestark-layout-sample
$ yarn run dev
```

```bash
$ cd icestark-vue2-child-sample
$ yarn run dev
```

Now, you can go to http://localhost:3000/vue2 to see micro vue2 app page.
