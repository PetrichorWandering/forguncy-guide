# 用户权限

## 用户管理

【<font color="#F3AA34">参考</font>】用户数据的「备份与还原」功能仅支持用户数据存储在内置库中。使用外联库的用户数据请自行做好备份操作。

## 权限

【<font color="#1677FF">推荐</font>】请明确区分业务角色与权限角色的边界划分。

::: info 📍 INFO
活字格的权限设计基于 RBAC（基于角色的权限控制）原则。角色可通过继承的方式实现权限组的效果。

- 业务角色：用来描述真实业务场景的角色，与用户直接关联。
- 权限角色：用来描述业务场景中的权限，不与用户关联。只能通过角色继承的方式与业务角色进行关联。
:::