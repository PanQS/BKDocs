# Summary

## 监控平台
* [产品简介](产品白皮书/intro/README.md)
* [核心优势](产品白皮书/intro/benefits.md)
* [术语解释](产品白皮书/concepts/glossary.md)
* [产品架构]()
    * [架构图](产品白皮书/concepts/architecture.md)
    * [数据模型](产品白皮书/concepts/datamodule.md)
* [快速入门]()
    * [入门须知](产品白皮书/quickstart/README.md)
    * [准备工作](产品白皮书/quickstart/prepare.md)
    * [权限申请](产品白皮书/quickstart/perm.md)
    * [快速接入](产品白皮书/quickstart/best-practices.md)
* [场景案例]()
    * [插件&采集相关]()
        * [如何通过脚本进行监控](产品白皮书/guide/script_collect.md)
        * [如何实现多实例采集](产品白皮书/guide/multi_instance_monitor.md)
        * [如何对开源组件进行监控](产品白皮书/guide/component_monitor.md)
        * [如何在线制作 Prometheus 插件](产品白皮书/guide/import_exporter.md)
        * [如何直接拉取 Prometheus 数据](产品白皮书/guide/howto_bk-pull.md)
        * [如何在线制作 DataDog 插件](产品白皮书/guide/import_datadog_online.md)
        * [如何线下制作 DataDog 插件](产品白皮书/guide/import_datadog_offline.md)
        * [如何在线制作 JMX 插件](产品白皮书/guide/plugin_jmx.md)
        * [无 Agent 如何实现采集](产品白皮书/guide/noagent_monitor.md)
        * [日志关键字事件](产品白皮书/guide/keywords_event.md)
        * [自定义上报工具](产品白皮书/guide/custom-report-tools.md)
    * [策略&告警相关]()
        * [如何对进程进行监控](产品白皮书/guide/process_monitor.md)
        * [如何监控日志平台的数据](产品白皮书/guide/log_monitor.md)
        * [如何监控计算平台的数据](产品白皮书/guide/bigdata_monitor.md)
        * [如何添加新的通知渠道](产品白皮书/guide/notify_setting.md)
        * [如何自定义通知模版](产品白皮书/guide/notify_case.md)
        * [如何设置告警回调](产品白皮书/guide/http_callback.md)
* [产品功能]()
    * [导航说明](产品白皮书/functions/menu.md)
    * [报表视图]()
        * [首页](产品白皮书/functions/report/home.md)
        * [仪盘表](产品白皮书/functions/report/new_dashboard.md)
    * [监控场景]()
        * [主机监控](产品白皮书/functions/scene/host-monitor.md)
        * [服务拨测](产品白皮书/functions/scene/dial.md)
    * [分析定位]()
        * [数据检索](产品白皮书/functions/analyze/data-search.md)
        * [事件中心](产品白皮书/functions/analyze/event.md)
    * [监控配置]()
        * [插件](产品白皮书/functions/conf/plugins.md)
        * [采集](产品白皮书/functions/conf/collect-tasks.md)
        * [策略](产品白皮书/functions/conf/rules.md)
        * [告警组](产品白皮书/functions/conf/alarm-group.md)
        * [屏蔽](产品白皮书/functions/conf/block.md)
        * [服务分类](产品白皮书/functions/conf/service-class.md)
        * [导入导出](产品白皮书/functions/conf/import-export.md)
        * [自定义上报](产品白皮书/functions/conf/custom-report.md)
    * [平台配置]()
        * [全局配置](产品白皮书/functions/global/admin-config.md)
        * [自监控](产品白皮书/functions/global/self-monitor.md)
    * [告警通知]()
        * [移动端](产品白皮书/functions/notify/h5_app.md)
        * [通知内容说明](产品白皮书/functions/notify/messages_example.md) 
    * [附录]()
        * [主机-操作系统-指标](产品白皮书/functions/addenda/host-metrics.md)
        * [主机-操作系统-系统事件](产品白皮书/functions/addenda/host-events.md)
        * [主机-进程-指标](产品白皮书/functions/addenda/process-metrics.md)
        * [内置官方插件](产品白皮书/functions/addenda/builtin-plugins.md)
        * [内置默认策略](产品白皮书/functions/addenda/builtin-rules.md)
        * [检测算法说明](产品白皮书/functions/addenda/algorithms.md)
        * [通知收敛和汇总机制](产品白皮书/functions/addenda/coverge.md)
        * [内置变量列表](产品白皮书/functions/addenda/variables.md)
        * [插件配置说明](产品白皮书/functions/addenda/plugins_explain.md)
        * [各种进程配置方法](产品白皮书/functions/addenda/process_cases.md)
        * [其他小功能](产品白皮书/functions/addenda/others.md)
* [二次开发]()
    * [Exporter 插件开发](产品白皮书/dev/plugin_exporter_dev.md)
    * [DataDog 插件开发](产品白皮书/dev/plugin_datadog_dev.md)
* [API 文档]()
    * [简介](6.0/API文档/monitor_v3/README.md)
    * [新增告警屏蔽](6.0/API文档/monitor_v3/zh-hans/add_shield.md)
    * [删除告警策略](6.0/API文档/monitor_v3/zh-hans/delete_alarm_strategy.md)
    * [删除策略配置 v2](6.0/API文档/monitor_v3/zh-hans/delete_alarm_strategy_v2.md)
    * [删除通知组](6.0/API文档/monitor_v3/zh-hans/delete_notice_group.md)
    * [解除告警屏蔽](6.0/API文档/monitor_v3/zh-hans/disable_shield.md)
    * [编辑告警屏蔽](6.0/API文档/monitor_v3/zh-hans/edit_shield.md)
    * [导出拨测任务配置](6.0/API文档/monitor_v3/zh-hans/export_uptime_check_task.md)
    * [查询事件流转记录](6.0/API文档/monitor_v3/zh-hans/get_event_log.md)
    * [获取告警屏蔽](6.0/API文档/monitor_v3/zh-hans/get_shield.md)
    * [获取 ES 数据](6.0/API文档/monitor_v3/zh-hans/get_ts_data.md)
    * [导入拨测节点配置](6.0/API文档/monitor_v3/zh-hans/import_uptime_check_node.md)
    * [导入拨测任务配置](6.0/API文档/monitor_v3/zh-hans/import_uptime_check_task.md)
    * [获取告警屏蔽列表](6.0/API文档/monitor_v3/zh-hans/list_shield.md)
    * [创建存储集群信息](6.0/API文档/monitor_v3/zh-hans/metadata_create_cluster_info.md)
    * [创建监控数据源](6.0/API文档/monitor_v3/zh-hans/metadata_create_data_id.md)
    * [创建事件分组](6.0/API文档/monitor_v3/zh-hans/metadata_create_event_group.md)
    * [创建监控结果表](6.0/API文档/monitor_v3/zh-hans/metadata_create_result_table.md)
    * [创建结果表的维度拆分配置](6.0/API文档/monitor_v3/zh-hans/metadata_create_result_table_metric_split.md)
    * [创建自定义时序分组](6.0/API文档/monitor_v3/zh-hans/metadata_create_time_series_group.md)
    * [删除事件分组](6.0/API文档/monitor_v3/zh-hans/metadata_delete_event_group.md)
    * [删除自定义时序分组](6.0/API文档/monitor_v3/zh-hans/metadata_delete_time_series_group.md)
    * [获取监控数据源具体信息](6.0/API文档/monitor_v3/zh-hans/metadata_get_data_id.md)
    * [查询事件分组具体内容](6.0/API文档/monitor_v3/zh-hans/metadata_get_event_group.md)
    * [获取监控结果表具体信息](6.0/API文档/monitor_v3/zh-hans/metadata_get_result_table.md)
    * [查询指定结果表的指定存储信息](6.0/API文档/monitor_v3/zh-hans/metadata_get_result_table_storage.md)
    * [获取自定义时序分组具体内容](6.0/API文档/monitor_v3/zh-hans/metadata_get_time_series_group.md)
    * [查询当前已有的标签信息](6.0/API文档/monitor_v3/zh-hans/metadata_list_label.md)
    * [查询监控结果表](6.0/API文档/monitor_v3/zh-hans/metadata_list_result_table.md)
    * [获取所有 transfer 集群信息](6.0/API文档/monitor_v3/zh-hans/metadata_list_transfer_cluster.md)
    * [修改存储集群信息](6.0/API文档/monitor_v3/zh-hans/metadata_modify_cluster_info.md)
    * [修改指定数据源的配置信息](6.0/API文档/monitor_v3/zh-hans/metadata_modify_data_id.md)
    * [修改事件分组](6.0/API文档/monitor_v3/zh-hans/metadata_modify_event_group.md)
    * [修改监控结果表](6.0/API文档/monitor_v3/zh-hans/metadata_modify_result_table.md)
    * [修改自定义时序分组](6.0/API文档/monitor_v3/zh-hans/metadata_modify_time_series_group.md)
    * [创建事件分组](6.0/API文档/monitor_v3/zh-hans/metadata_query_event_group.md)
    * [获取自定义时序分组具体内容](6.0/API文档/monitor_v3/zh-hans/metadata_query_tag_values.md)
    * [查询事件分组](6.0/API文档/monitor_v3/zh-hans/metadata_query_time_series_group.md)
    * [将指定的监控单业务结果表升级为全业务结果表](6.0/API文档/monitor_v3/zh-hans/metadata_upgrade_result_table.md)
    * [保存告警策略](6.0/API文档/monitor_v3/zh-hans/save_alarm_strategy.md)
    * [保存告警策略 v2](6.0/API文档/monitor_v3/zh-hans/save_alarm_strategy_v2.md)
    * [保存通知组](6.0/API文档/monitor_v3/zh-hans/save_notice_group.md)
    * [查询告警策略](6.0/API文档/monitor_v3/zh-hans/search_alarm_strategy.md)
    * [查询告警策略列表](6.0/API文档/monitor_v3/zh-hans/search_alarm_strategy_v2.md)
    * [查询事件](6.0/API文档/monitor_v3/zh-hans/search_event.md)
    * [查询通知组](6.0/API文档/monitor_v3/zh-hans/search_notice_group.md)
    * [启停告警策略](6.0/API文档/monitor_v3/zh-hans/switch_alarm_strategy.md)
    * [批量更新策略局部配置](6.0/API文档/monitor_v3/zh-hans/update_partial_strategy_v2.md)
* [产品功能 FAQ]()
    * [采集相关](产品白皮书/faq/collect_faq.md)
    * [主机监控相关](产品白皮书/faq/host_monitor.md)
* [产品运行异常维护]()
    * [自监控服务异常](产品白皮书/运行异常维护FAQ/自监控异常.md) 
* [结语](产品白皮书/conclusion/conclusion.md)