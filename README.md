# simple-bpm-php-engine

Target: Simple & Practical & Production-ready

https://www.processon.com/view/link/5724e3f4e4b0c618eb3dfd7a

<img src='https://www.processon.com/chart_image/5724e338e4b0c618eb3dfafc.png'/>

Substantially, execute logic according to the flow design by the BPMN Editor (from http://bpmn.io/ or http://processon.com)...

= Usage (Design Assumption)

<pre>
$rt=cmp::runBPM(array(
	"bpmn_name"=>"TestJob_PingSystemAlive",
	"bpmn_activity"=>bpmn_activity,
	"bpmn_mode"=>"Default",//Default|Orm|Session|Mysql|MongoDB|Redis|... , Default is Sessionless & Sync
	//"bpmn_timeout"=>30,//0 for infinite
));
println($rt);
</pre>

# BPMN2 XML Designer/Editor  (Camunda)

Official Website => http://bpmn.io/

Download =>  http://bpmn.io/getting-started/#download

WebApp => http://bpmn.io/desktop/

# BPMN2 XML Designer/Editor  (ProcessOn)

Official Website => http://processon.com/

# Dependency

* CMP PHP Framework (Other Framework is easy to support) => http://cmptech.info/




