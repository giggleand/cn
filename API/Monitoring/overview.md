# JCLOUD MONITOR API


## 简介
monitor API


### 版本
v1


## API
|接口名称|请求方式|功能描述|
|---|---|---|
|**batchCreateAlarms**|POST|批量创建报警规则，可以为多个实例创建多个报警规则。|
|**batchDeleteAlarms**|DELETE|批量删除规则|
|**batchDescribeMetricData**|GET|查看某资源多个监控项数据|
|**batchDisableAlarms**|POST|批量禁用规则|
|**batchEnableAlarms**|POST|批量启用规则|
|**createAlarm**|POST|创建报警规则，可以为某一个实例创建报警规则，也可以为多个实例同时创建报警规则。|
|**describeAlarmContacts**|GET|查询规则的报警联系人|
|**describeAlarmHistory**|GET|查询报警历史</br>检索条件组合优先级从高到低为</br>1. serviceCode</br>1.1 serviceCode + resourceId</br>1.2 serviceCode + resourceIds</br>2. serviceCodes</br>3. 用户所有规则|
|**describeAlarms**|GET|查询规则, 查询参数组合及优先级从高到低为：</br>1：serviceCode不为空</br>1.1：serviceCode + resourceId</br>1.2: serviceCode + resourceIds</br>2：serviceCodes不为空</br>3: 所有规则|
|**describeAlarmsByID**|GET|查询规则详情|
|**describeMetricData**|GET|查看某资源的监控数据|
|**describeMetrics**|GET|根据产品线查询可用监控项列表|
|**describeMetricsForCreateAlarm**|GET|查询可用创建监控规则的指标列表|
|**disableAlarm**|POST|禁用报警规则。报警规则禁用后，将停止探测实例的监控项数据。|
|**enableAlarm**|POST|启用报警规则，当客户的报警规则处于停止状态时，可以使用此接口启用报警规则。|
|**lastDownsample**|GET|查看某资源的最后一个点|
|**putMetricData**|POST|该接口为自定义监控数据上报的接口，方便您将自己采集的时序数据上报到云监控。可上报原始数据和已聚合的统计数据。支持批量上报方式。单次请求最多包含 50 个数据点；数据大小不超过 256k。|
|**updateAlarm**|PATCH|修改已创建的报警规则|
