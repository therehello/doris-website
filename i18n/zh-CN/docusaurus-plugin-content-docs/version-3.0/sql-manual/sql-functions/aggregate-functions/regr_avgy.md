---
{
    "title": "REGR_AVGY",
    "language": "zh-CN"
}
---

<!-- 
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at
  http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

## REGR_AVGY
### Description
#### Syntax

`regr_avgy(y, x)`

计算线性回归分析中自变量 `y` 的平均值。

### example

```sql
mysql> select regr_avgy(y, x) from t;
+--------------------+
| regr_avgy(y, x)    |
+--------------------+
| 60.417901200833334 |
+--------------------+
1 row in set (0.046 sec)
```

### keywords
REGR_AVGY