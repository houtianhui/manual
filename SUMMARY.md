# Summary

* [前言](README.md)
* [部署](部署/README.md)
  * [安装步骤](部署/TBDS部署.md)
* [开始](开始/README.md)
* \[平台管理\]
  * [用户管理](平台管理/usermanage.md)
  * [项目管理](平台管理/projectmanage.md)
  * [系统设置](平台管理/systemconfig.md)
* [\[组件访问开发\]](zu-jian-fang-wen-kai-53d15d.md)
  * [kafka](组件使用/kafka/kafka.md)
  * [hadoop](组件使用/hadoop/hadoop.md)
  * [hbase](组件使用/hbase/hbase.md)
  * [accessKey](组件使用/accesskey/acckey.md)
  * [hive](组件使用/hive/hive.md)
  * [spark](组件使用/spark/spark.md)
  * [ftp](组件使用/ftpOverHdfs/ftp.md)
  * [portalApi](组件使用/portalApi/portalApi.md)
  * [hermes](组件使用/hermes/hermesapi.md)
  * [\[代码访问组件demos\]](组件使用/kafka/dai-ma-fang-wen-zu-jian-demos.md)
    * [hbase](组件使用/kafka/dai-ma-fang-wen-zu-jian-demos/hbase.md)
    * [hdfs](组件使用/kafka/dai-ma-fang-wen-zu-jian-demos/hdfs.md)
    * [kafka](组件使用/kafka/dai-ma-fang-wen-zu-jian-demos/kafka.md)
    * [hive](组件使用/kafka/dai-ma-fang-wen-zu-jian-demos/hive.md)
* [\[数据接入\]](shu-ju-gong-53825d.md)
  * [数据接入](/数据接入/数据接入/tdbank_intro.md)
    * [TDBank产品化介绍及使用指引](/数据接入/数据接入/tdbank_intro.md)
    * [TDBank数据接入指引](/数据接入/数据接入/tdbank_guide.md)
    * [TDBank采集接口详解](/数据接入/数据接入/tdbank_conf.md)
    * [OGG Flume Adapter 部署文档](/数据接入/数据接入/ogg_flume_adapter.md)
  * [Hippo管理](/数据接入/Hippo管理/hippo_mamage.md)
  * [进度监控](/数据接入/进度监控/progress_monitor.md)
  * [血缘分析](/数据接入/血缘分析/lineage_fenxi.md)
* \[实时计算\]
  * [任务管理](/实时计算/任务管理/task_manage.md)
  * [库表模板管理](/实时计算/库表模板管理/table_model_mamage.md)
* \[数据分析\]
  * [数据交互](shu-ju-fen-67905d.md)
* [任务调度](/workflow/readme.md)
  * [工作流](/workflow/workflow/readme.md)
    * [基本概念](/workflow/workflow/basicConcept.md)
    * [操作指引](/workflow/workflow/guide.md)
    * [任务基本信息](/workflow/workflow/runnerBasicInfo.md)
    * [任务调度设置](/workflow/workflow/runnerCycle.md)
    * [任务参数配置](/workflow/workflow/runners.md)
      * [shell 脚本](/workflow/workflow/runners/shell.md)
      * [ftp导入hdfs](/workflow/workflow/runners/ftp2hdfs.md)
      * [kafka导入hbase](/workflow/workflow/runners/kafka2hbase.md)
      * [kafka导入hdfs](/workflow/workflow/runners/kafka2hdfs.md)
      * [hdfs导出mysql](/workflow/workflow/runners/hdfs2mysql.md)
      * [hdfs导出hbase](/workflow/workflow/runners/hdfs2hbase.md)
      * [hive sql 脚本](/workflow/workflow/runners/hivesql.md)
      * [hive导入hdfs](/workflow/workflow/runners/hive2hdfs.md)
      * [hdfs导出DB\(mysql,postgreSQL,sql server\)](/workflow/workflow/runners/hdfs2db.md)
      * [hdfs导出mysql](/workflow/workflow/runners/hdfs2mysql.md)
      * [tstorm任务](/workflow/workflow/runners/customerTstorm.md)
    * [补充](/workflow/workflow/other.md)
      * [手动安装runner服务](/workflow/workflow/more/addrunner.md)
      * [自定义任务开发文档](/workflow/workflow/more/user-defined-dev.md)
    * [常见问题定位和解决方式](/workflow/workflow/qa.md)
      * [常用操作](/workflow/workflow/qa/common_operation.md)
      * [实时接入任务hdfs2hive \(tdsort\)](/workflow/workflow/qa/hdfs2hive_tdsort.md)
  * [任务管理](/workflow/tasks/readme.md)
  * [服务器配置](/workflow/services/readme.md)
    * [基本概念](workflow/services/introduce.md)
    * [操作指南](workflow/services/operation.md)
* [\[Tstorm\]](tstorm.md)
  * [Tstorm介绍](/tstorm/readme.md)
  * [开发实例](/tstorm/demo/readme.md)
    * [wordcount](/tstorm/demo/wordcountTstormDemo.md)
* \[数据展现\]
  * [自助报表](/数据展现/idea.md)
* \[数据资产\]
  * [库表管理](数据资产/库表管理/readme.md)
    * [可管理库表](数据资产/库表管理/manage_table.md)
    * [可读写库表](数据资产/库表管理/rw_table.md)
    * [无归属库表](数据资产/库表管理/nobelong_table.md)
    * [维表管理](数据资产/库表管理/meta_table.md)
  * [数据血缘](数据资产/数据血缘/lineage.md)
  * [数据提取](数据资产/数据提取/readme.md)
* \[运维中心\]
  * [全局概况]
  * [系统运维]
    * [组件部署](平台运维/组件部署/文档.md)
    * [链接归集](平台运维/链接归集/links.md)
    * [诊断](平台运维/诊断/诊断.md)
    * [备份](平台运维/备份/backup.md)
  * [访问管理](数据治理/数据权限/数据权限.md)
  * [文件管理](平台运维/文件管理/文件管理.md)
  * [监控告警]
    * [监控](平台运维/监控指标/document.md)
    * [告警](平台运维/诊断/gao-8b665d.md)

* \[机器学习\]
  * [系统简介](/机器学习/README.md)
  * [工作流](/机器学习/gong-zuo-liu.md)
    * [新建工程](/机器学习/new_project.md)
    * [新建工作流](/机器学习/new_workflow.md)
    * [创建和配置节点](/机器学习/config_parameter.md)
    * [运行](/机器学习/run.md)
    * [日志查看](/机器学习/log_view.md)
  * [数据输入输出](/机器学习/dataset.md)
  * [组件](/机器学习/zu-jian.md)
    * [Spark组件](/机器学习/spark.md)
    * [Sparkstreaming组件](/机器学习/spark-streaming.md)
    * [pySpark组件](/机器学习/pyspark.md)
  * [多实例并发](/机器学习/duo-shi-li-bing-fa.md)
    * [3种方式驱动实例](/机器学习/multiple_drive.md)
    * [实例查询](/机器学习/instanceview.md)
    * [历史实例](/机器学习/history_instance.md)
