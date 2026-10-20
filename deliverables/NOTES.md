# Lite notes

## English

This slice is the namespace read-only set for `shop/namespace-read`, plus the ClusterRole `cluster-read` without its binding. Verbs are `get`, `list`, and `watch`. The Role does not name secrets. `automountServiceAccountToken` is false.

The ClusterRoleBinding that would grant `cluster-read` in every namespace is not in this slice. The deploy-bot Role, RoleBinding, and ServiceAccount are not in this slice either.

apiVersion on the Role and ClusterRole is `rbac.authorization.k8s.io/v1`. Check upstream docs before you change it.

## 中文

这一份是 `shop/namespace-read` 的命名空间只读套件，以及没有绑定的 ClusterRole `cluster-read`。动词只有 `get`、`list`、`watch`。Role 不包含 secrets。`automountServiceAccountToken` 为 false。

会在每个命名空间授予 `cluster-read` 的 ClusterRoleBinding 不在这一份里。部署机器人的 Role、RoleBinding 和 ServiceAccount 也不在这一份里。

Role 和 ClusterRole 的 apiVersion 是 `rbac.authorization.k8s.io/v1`。修改之前请核对上游文档（check upstream docs）。
