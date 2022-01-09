---
title: login()
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import CodeBlock from '@theme/CodeBlock';
import LoginJs from '!!raw-loader!./snippets/login-js.md';
import LoginApi from '!!raw-loader!./snippets/login-api.md';

Log in an existing user.
<Tabs>
  <TabItem value="javascript" label="Javascript" default>
    <CodeBlock className="language-jsx">
      {LoginJs}
    </CodeBlock>
  </TabItem>
  <TabItem value="API" label="API">
    <CodeBlock className="language-jsx" title="[POST]">
      {LoginApi}
    </CodeBlock>
  </TabItem>
</Tabs>

