# Project setup

## About

Udemy > [FastAPI + ReactによるフルスタックWeb開発](https://ibisjp.udemy.com/course/farm-stack-react-fastapi/learn/lecture/29201422#overview)

## Create react app + install packgages

1. 以下、コマンドを実行
    ```
    npx create-react-app . --template redux-typescript
    yarn add react-query@3.39.0
    yarn add react-router-dom@5.3.0 @types/react-router-dom@5.3.1
    yarn add axios@0.27.2 @heroicons/react@1.0.6
    yarn add -D tailwindcss postcss autoprefixer
    npx tailwindcss init -p
    ```

2. src/index.tsx のStrictModeをコメントアウト（[参考](https://ibisjp.udemy.com/course/farm-stack-react-fastapi/learn/lecture/29319020#overview)）
3. tailwind.config.js のcontentを修正([参考](https://ibisjp.udemy.com/course/farm-stack-react-fastapi/learn/lecture/29985082#overview))
4. src.index.css内を下記に置き換える

    ```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```

1. 下記コマンドから実行
    ```
    yarn start
    ```

