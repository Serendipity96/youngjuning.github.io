---
title: 留言板
nav:
  title: 留言板
  order: 4
hero:
  title: 留言板
  desc: 轻轻地你走了，不带走一片云彩
---

```jsx
/**
 * inline: true
 */
import React from 'react';
import 'gitalk/dist/gitalk.css';
import GitalkComponent from 'gitalk/dist/gitalk-component';

export default () => {
  return (
    <GitalkComponent
      options={{
        clientID: 'a6e0d6a84dbf93dd00f3',
        clientSecret: '0c9c5fff9e132c7e85ccc08633629706acfc33e4',
        repo: 'youngjuning.github.io',
        owner: 'youngjuning',
        admin: ['youngjuning'],
      }}
    />
  );
};
```