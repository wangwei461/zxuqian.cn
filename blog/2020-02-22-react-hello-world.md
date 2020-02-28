---
id: react-hello-world
title: 创建第一个 React Hello World 应用
author: 峰华
author_title: 前端工程师 / B站UP主
author_url: https://github.com/ zxuqian
author_image_url: https://tvax3.sinaimg.cn/crop.0.0.1080.1080.180/b2745d44ly8g8s4muqeggj20u00u0n0k.jpg?KID=imgbed,tva&Expires=1582389585&ssig=EvXmyu%2FXsX
tags: [react, javascript, 前端]
---

import useBaseUrl from '@docusaurus/useBaseUrl';

创建第一个 React Hello World 程序（代码可实时编辑）

```jsx live
function App() {
  const H1 = styled.h1`
    color: #34ace0;
  `;

  function Greeting() {
    return <H1>Hello World</H1>;
  }

  return <Greeting />;
}
```

<!-- <img alt="" src={useBaseUrl('img/2020-02-22-react-hello-world/2020-02-26-12-33-21.png')} /> -->