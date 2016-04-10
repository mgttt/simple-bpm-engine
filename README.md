# simple-bpm-php-engine

Target: Simple & Practical & Production-ready

<img src="https://www.processon.com/chart_image/57093a33e4b04878f868f640.png" />
<img src="../../raw/master/sample.bpm.ping.system.png"/>

Substantially, execute logic according to the flow design by the BPMN Editor (from http://bpmn.io/)...

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

# BPMN2 XML Designer/Editor 

Official Website => http://bpmn.io/

Download =>  http://bpmn.io/getting-started/#download

WebApp => http://bpmn.io/desktop/


# Dependency

* CMP PHP Framework (Other Framework is easy to support) => http://cmptech.info/




