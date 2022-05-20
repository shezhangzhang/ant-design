---
order: 2
title:
  zh-CN: 小型进度条
  en-US: Mini size progress bar
---

## zh-CN

适合放在较狭窄的区域内。

## en-US

Appropriate for a narrow area.

```tsx
import React from 'react';
import { Progress } from 'antd';

const App: React.FC = () => (
  <div style={{ width: 170 }}>
    <Progress percent={30} size="small" />
    <Progress percent={50} size="small" status="active" />
    <Progress percent={70} size="small" status="exception" />
    <Progress percent={100} size="small" />
  </div>
);

export default App;
```