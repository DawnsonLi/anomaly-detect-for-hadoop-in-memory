# hadoop大数据平台异常探测探索
## hadoop metrics<br>
基于hadoop metrics,我们可以实时的获取包含hadoop系统上各个组件的metrics信息，这些metrics用于监控，表现调优和debug,并可用于troubleshooting<br>系统中异常变量的含义均保留使用hadoop metrics的名称<br>详情参见hadoop官方文档http://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-common/Metrics.html<br>
## 项目使用工具 <br>
使用ganglia API获取时间序列数据（参考doc目录）
