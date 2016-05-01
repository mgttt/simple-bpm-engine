# simple-bpm-engine

Target: Simple & Practical & Production-ready

Design: 
https://www.processon.com/embed/570759a0e4b0dcddf98190f1
![alt tag](https://www.processon.com/chart_image/5715ad55e4b0d89bd2587fa7.png)

Real World Example: 
https://www.processon.com/view/link/5724e3f4e4b0c618eb3dfd7a
![alt tag](https://www.processon.com/chart_image/57255226e4b0c618eb3e5bf2.png)

Substantially, execute logic according to the flow design by the BPMN Editor (from http://bpmn.io/ or http://processon.com)...

= Design Assumption
http://share.cmptech.info/reference/BPM.zh-cn.utf8.htm

= Usage

Example:
```php
$rt=cmp::runBPM(array(
	"bpmn_name"=>"TestJob_PingSystemAlive",
	"bpmn_activity"=>bpmn_activity,
	"bpmn_mode"=>"Default",//Default|Orm|Session|Mysql|MongoDB|Redis|... , Default is Sessionless & Sync
	//"bpmn_timeout"=>30,//0 for infinite
));
println($rt);
```

# BPMN2 XML Designer/Editor  (Camunda)

Official Website => http://bpmn.io/

Download =>  http://bpmn.io/getting-started/#download

WebApp => http://bpmn.io/desktop/

# BPMN2 XML Designer/Editor  (ProcessOn)

Official Website => http://processon.com/

# Dependency (PHP)

* CMP PHP Framework (Other Framework is easy to support) => http://cmptech.info/




