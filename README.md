<div align="center"> 

![fystart](/public/favicon.ico)
# [Fystart](https://fystart.cn/)

[![GitHub stars](https://img.shields.io/github/stars/zmh-program/fystart?style=flat-square)](https://fystart.cn)
[![GitHub forks](https://img.shields.io/github/forks/zmh-program/fystart?style=flat-square)](https://fystart.cn)
[![GitHub issues](https://img.shields.io/github/issues/zmh-program/fystart?style=flat-square)](https://fystart.cn)
[![GitHub license](https://img.shields.io/github/license/zmh-program/fystart?style=flat-square)](https://fystart.cn)

#### A simple and intuitive browser start page
#### 一个简洁的起始页

</div>


## Features | 功能
- 🍏 一言 
  - 🍏 Quotes
- 🍋 自定义设置
  - 🍋 Customizable Settings
- 🍎 ChatGPT 搜索建议
  - 🍎 ChatGPT Search Suggestions
- 🍉 翻译 / Github 搜索
  - 🍉 Translation / GitHub Search
- 🍇 工具箱
  - 🍇 Tool Box
- 🍐 搜索引擎建议
  - 🍐 Search Engine Suggestions
- 🎃 PWA 应用
  - 🎃 PWA Application
- ✨ 离线访问 (Service Worker)
  - ✨ Offline Requests (Service Worker)
- ⚡ 搜索引擎优化
  - ⚡ SEO (Search Engine Optimization) 
- ❤ 国际化支持
  - ❤ i18n (Internationalization) Support
    - ✔ 🇨🇳 简体中文 (Simplified Chinese)
    - ✔ 🇨🇳 🇹🇼 繁體中文 (Traditional Chinese)
    - ✔ 🇺🇸 English (United States)
    - ✔ 🇷🇺 Русский (Russian)
    - ✔ 🇫🇷 Français (French)
    - ✔ 🇯🇵 日本語 (Japanese)




## ScreenShot | 快照
![main](/screenshot/main.png)

![search](/screenshot/search.png)

![customize](/screenshot/customize.png)

![settings](/screenshot/settings.png)

![engine](/screenshot/engine.png)

![i18n](/screenshot/i18n.png)


### Get Started | 开始
npm (yarn, pnpm)
```shell
npm install
npm run dev

cd backend
go run .
```

### Configuration | 配置
/src/assets/script/config.ts
```ts
export const endpoint = "https://api.fystart.cn/gpt";
```
/backend/config.yaml
```yaml
debug: true
api_key: 'sk-...'
redis:
  host: "localhost"
  port: 6379
  password: ""
  db: 0
```

### Build | 构建
```shell
npm run build
cd backend && go build .
```

### License | 开源协议
[MIT](/LICENSE)

### Security Policy | 安全政策
[Security Policy](/SECURITY.md)

### Privacy Policy | 隐私政策
[Privacy Policy](/PRIVACY.md)

### Sponsor | 赞助
no one
