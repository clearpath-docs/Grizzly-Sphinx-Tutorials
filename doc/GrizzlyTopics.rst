Grizzly ROS Topics
=========================  


.. raw:: html

	<div class="wy-table-responsive">
	<table border="1" class="docutils">
	<col width="25%">
	<col width="25%">
	<thead valign="bottom">
	<tr class="row-odd">
		<th>Topic</th>
		<th>Type</th>
		<th>Purpose</th>
	</tr>
	</thead>
	 <tbody valign="top">
	  <tr class="row-even">
	    <td>/cmd_vel</td>
	    <td>geometry_msgs/Twist</td>
	    <td>Kinematic motion commands to Grizzly</td>	  
	  </tr>

	  <tr class="row-even">
	    <td>/cmd_drive</td>
	    <td>grizzly_msgs/Drive</td>
	    <td>Per-wheel motion commands to Grizzly</td>	  
	  </tr>

	  	  <tr class="row-even">
	    <td>/encoder</td>
	    <td>nav_msgs/Odometry</td>
	    <td>Dead reckoning feedback from Grizzly</td>	  
	  </tr>
	 
	 	  	  <tr class="row-even">
	    <td>/diagnostics</td>
	    <td>diagnostic_msgs/DiagnosticArray</td>
	    <td>System diagnostic output</td>	  
	  </tr>


	 	  	  <tr class="row-even">
	    <td>/mcu/energy</td>
	    <td>std_msgs/Float32</td>
	    <td>Battery charge estimate</td>	  
	  </tr>



  	  <tr class="row-even">
	    <td>/mcu/estop</td>
	    <td>std_msgs/Bool2</td>
	    <td>Emergency stop trigger</td>	  
	  </tr>

	    	  <tr class="row-even">
	    <td>/mcu/status</td>
	    <td>grizzly_msgs/RawStatus</td>
	    <td>Raw status output from MCU</td>	  
	  </tr>



	    	  <tr class="row-even">
	    <td>/motors/*/status</td>
	    <td>roboteq_msgs/Status</td>
	    <td>Raw status output from a given motor controller</td>	  
	  </tr>


	    	  <tr class="row-even">
	    <td>/motors/*/feedback</td>
	    <td>roboteq_msgs/Feedback</td>
	    <td>Raw feedback from a given motor controller</td>	  
	  </tr>





	 



	  </tbody>
	</table>

