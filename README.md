# 一个Vue3项目的基本环境模板

1. [vite](https://cn.vitejs.dev/guide/#scaffolding-your-first-vite-project) 构建项目
2. 安装 [eslint,](https://zh-hans.eslint.org/docs/latest/use/getting-started) [prettier](https://prettier.io/docs/en/install) 以及[eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)
3. 安装 [tailwindcss](https://tailwindcss.com/docs/guides/vite)，[prettier-plugin-tailwindcss](https://tailwindcss.com/blog/automatic-class-sorting-with-prettier)
4. 安装 [husky](https://prettier.io/docs/en/install#git-hooks)

```json
"lint-staged": {
    "*.{vue,js,ts,jsx,tsx,md,json,html,css,scss}": [
      "eslint --fix  --cache",
      "prettier --write  --cache"
    ]
  }
```
