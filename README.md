# K8s RBAC Templates (Lite)

## English

A free slice: the namespace read-only account `shop/namespace-read`, the ClusterRole `cluster-read` without a binding, and a filled read-only example in namespace `checkout`. The full pack adds the opt-in ClusterRoleBinding, the deploy-bot Role and ServiceAccount, the ClusterRole bound by a RoleBinding in one namespace, the checkout deploy example, the local checker, tests, and the longer bilingual notes.

### Deliverables

- `deliverables/NOTES.md` — short English and Chinese notes for this slice
- `deliverables/read-only/namespace.yaml` — Namespace `shop`
- `deliverables/read-only/serviceaccount.yaml` — ServiceAccount `shop/namespace-read`
- `deliverables/read-only/role.yaml` — Role `namespace-read`
- `deliverables/read-only/rolebinding.yaml` — RoleBinding `namespace-read`
- `deliverables/read-only-cluster/clusterrole.yaml` — ClusterRole `cluster-read` with no binding in this slice
- `examples/checkout/README.md` — concrete names for the filled example
- `examples/checkout/namespace.yaml` — Namespace `checkout`
- `examples/checkout/read-only/serviceaccount.yaml` — ServiceAccount `checkout/checkout-read`
- `examples/checkout/read-only/role.yaml` — Role `checkout-read`
- `examples/checkout/read-only/rolebinding.yaml` — RoleBinding `checkout-read`
- `LICENSE` — MIT

## 中文

免费切片：命名空间只读账号 `shop/namespace-read`，没有绑定的 ClusterRole `cluster-read`，以及命名空间 `checkout` 里填好的只读示例。完整版另有可选的 ClusterRoleBinding、部署机器人的 Role 和 ServiceAccount、用 RoleBinding 限制在一个命名空间里的 ClusterRole、checkout 的部署示例、本地检查脚本、测试，以及更长的双语笔记。

### 交付文件

- `deliverables/NOTES.md` — 本切片的简短中英笔记
- `deliverables/read-only/namespace.yaml` — Namespace `shop`
- `deliverables/read-only/serviceaccount.yaml` — ServiceAccount `shop/namespace-read`
- `deliverables/read-only/role.yaml` — Role `namespace-read`
- `deliverables/read-only/rolebinding.yaml` — RoleBinding `namespace-read`
- `deliverables/read-only-cluster/clusterrole.yaml` — ClusterRole `cluster-read`，本切片里没有绑定
- `examples/checkout/README.md` — 填好示例的具体名字
- `examples/checkout/namespace.yaml` — Namespace `checkout`
- `examples/checkout/read-only/serviceaccount.yaml` — ServiceAccount `checkout/checkout-read`
- `examples/checkout/read-only/role.yaml` — Role `checkout-read`
- `examples/checkout/read-only/rolebinding.yaml` — RoleBinding `checkout-read`
- `LICENSE` — MIT

Full version: GUMROAD_URL
