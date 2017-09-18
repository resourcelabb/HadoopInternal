# Apache Hadoop (MapReduce) Internals - Diagrams
This project contains several diagrams describing [Apache Hadoop](http://hadoop.apache.org/) internals (2.3.0 or later). Even if these diagrams are NOT specified in any formal or unambiguous language (e.g., UML), they should be reasonably understandable (here some **[diagram notation conventions](DiagramConventions)**) and useful for any person who want to grasp the main ideas behind Hadoop. Unfortunately, not all the internal details are covered by these diagrams. You are free to help :)

<br />  

<div style="text-align: center;">
<iframe src="http://www.slideshare.net/slideshow/embed_code/34080760" width="597" height="486" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px 1px 0; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="https://www.slideshare.net/EmilioCoppa/hadoop-internals" title="Hadoop Internals (2.3.0 or later)" target="_blank">Hadoop Internals (2.3.0 or later)</a> </strong> from <strong><a href="http://www.slideshare.net/EmilioCoppa" target="_blank">Emilio Coppa</a></strong> </div>
</div>

<br />
<table>
<tr>

<th>Actors</th>
<th>Tasks</th>
<th>Model of computation</th>
<th>Extra</th>

</tr>
<tr>

<td>
  <li><a href="JobSubmitter.html">Job Submitter</a></li>
  <li><a href="NodeManager.html">Node Manager</a></li>
  <li><a href="ResourceManager.html">Resource Manager</a></li>
  <li><a href="ApplicationMaster.html">Application Master</a></li> 
  <br /> 
</td>

<td>
  <li><a href="MapTask.html">Map Task</a></li>
  <li><a href="ReduceTask.html">Reduce Task</a></li>
  <li><a href="MapReduceMerge.html">Merger</a></li>
  <li><a href="MapReduceInput.html">Input</a></li>
  <br />
</td>

<td>
  <li><a href="Job.html">Job</a></li>
  <li><a href="Task.html">Task</a></li>
  <li><a href="TaskAttempt.html">Task Attempt</a></li>
  <li><a href="Application.html">Application</a></li>
  <li><a href="Container.html">Container</a></li>
</td>

<td>
  <li><a href="AsyncDispatcher.html">Async Dispatcher</a></li>
  <li><a href="LocalizedResource.html">Localized Resource</a></li>
  <li><a href="ContainerAllocator.html">Container Allocator [AM]</a></li>
  <li><a href="ContainerLauncher.html">Container Launcher [AM]</a></li>
  <li><a href="ContainersLauncher.html">Containers Launcher [NM]</a></li>
</td>
</tr>
</table>
