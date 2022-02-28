# 1-1. parcel npm 파일 정적연결
```
npm i -D parcel-plugin-static-files-copy
```
# 1-2. autoprefixer 설치
```
npm i -D postcss 
nom i -D autoprefixer
```
# 1-3. postcssrc.js 연동

```
module.exports = {
    plugins: [
        require('autoprefixer')
    ]
}
```
---

# 2-1 babel 설치
```
<-- babel 설치 -->
npm i -D @babel/core
npm i -D @bable/preset -env
<-- babel: async await 함수 bundler 연동 -->
npm i -D @babel/plugin-transform-runtime
```

# 2-2 .babelrc.js 연동

```
module.exports = {
    presets: ['@babel/preset-env']
    plugins: [
        ['@bable/plugin-transfrom-runtime']
    ]
}
```