---
title: CSIStorageCapacity
content_type: feature_gate
_build:
  list: never
  render: false
---
<!--
Enables CSI drivers to publish storage capacity information
and the Kubernetes scheduler to use that information when scheduling pods. See
[Storage Capacity](/docs/concepts/storage/storage-capacity/).
Check the [`csi` volume type](/docs/concepts/storage/volumes/#csi) documentation for more details.
-->
启用 CSI 驱动发布存储容量信息，
以及 Kubernetes 调度器在调度 Pods 时使用该信息。
详情见[存储容量](/zh-cn/docs/concepts/storage/storage-capacity/)。
更多详情请参阅 [`csi` 卷类型](/zh-cn/docs/concepts/storage/volumes/#csi)文档。

