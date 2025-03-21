# 流水线编辑页

流水线的核心页面之一，可通过可视化界面生成 CI 流水线。

## 功能区介绍

![png](../../assets/service_pipeline_edit.png)

1. 流水线面包屑：此处有两个点击事件
   - 点击流水线名称：快速进入流水线执行历史
   - 点击名称右侧的小三角：快速切换至其它流水线
2. 流水线编辑标签，可以在流水线编排页、基础设置之间互相切换：
   - 流水线编排区：参考第 3 点
   - 流水线基础设置：
3. 流水线编排区：遵守 [流水线核心理念](../../Concepts/Learn-pipeline-in-5min.md)的可视化编排区域
4. 流水线操作区，包含如下常用操作集合：
   - 保存：每点一次保存，会生成一个从 1 开始自增的编排版本号，可用于回滚
   - 执行：基于当前的编排版本号，生成一个快照流水线任务
   - 重命名：对当前流水线名称进行改名
   - 收藏：将当前流水线收藏，可以在“我的收藏”视图中查看
   - 导出：将当前流水线导出为 JSON，可以在新建流水线时导入（可跨不同项目）
   - 复制为：基于当前流水线的当前编排版本号，复制一个新的流水线“旧流水线名称_copy”
   - 另存为模板：将当前流水线的编排保存为流水线模板
   - 删除：软删除，将放入流水线回收站

## 接下来你可能需要

* 编排流水线
   * 基本操作
      * [Stage 准入](pipeline-edit-guide/gui.md)
      * [为流水线开启自定义构建号](pipeline-edit-guide/alias-buildno.md)
      * [锁定流水线](pipeline-edit-guide/disable-pipeline.md)
   * 触发器
      * [gitlab 触发](pipeline-triggers/pipeline-trigger-gitlab.md)
      * [手动触发](pipeline-triggers/pipeline-trigger-manual.md)
      * [定时触发](pipeline-triggers/pipeline-trigger-timer.md)
      * [远程触发](/pipeline-triggers/pipeline-trigger-remote.md)
   * 流水线变量
      * [变量的基本使用](pipeline-variables/pipeline-variables-shell-batch.md)
      * [使用变量控制流水线流程](pipeline-variables/pipeline-variables-flow-control.md)
      * [使用备注变量](pipeline-variables/pipeline-variables-remark.md)
      * [凭证变量](pipeline-variables/pipeline-variables-ticket.md)
* [bk-ci 导航条](../Console.md)
* [流水线列表页](pipeline-list.md)
* [流水线任务历史](pipeline-history.md)
* [流水线任务详情页](pipeline-detail.md)
