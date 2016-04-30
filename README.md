# simple-bpm-php-engine

Target: Simple & Practical & Production-ready

https://www.processon.com/view/link/5724e3f4e4b0c618eb3dfd7a

<pre>
<iframe id="embed_dom" name="embed_dom" frameborder="0" style="border:1px solid #000;display:block;width:430px; height:320px;" src="https://www.processon.com/embed/57047f51e4b0bf3d8fdfee5f"></iframe>
</pre>

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




