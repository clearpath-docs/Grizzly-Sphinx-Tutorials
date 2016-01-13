Upstart Installation
=========================  

The Grizzly computer automatically starts a ros master and all associated device drivers on boot. The grizzly-core job comes up with the br0 network device by default, which is a bridge connected to wireless or wired networks, depending on customer configuration. You can stop, start, and restart the job like any other upstart job:

.. code:: bash

	sudo service grizzly-core restart

To add more launch files to the job, copy them into the /etc/ros/hydro/Grizzly-core.d folder. Next time the job comes up, your software will launch along with it. For details, please see the `robot_upstart <http://wiki.ros.org/robot_upstart>`_ package.

If the computer you are setting up is one purchased from Clearpath Robotics with a factory sensor suite, the install script may be able to automatically detect some of your devices and add appropriate launchers files to the grizzly-core job.

For more information or to receive a quote, please `visit us online <http://clearpathrobotics.com/grizzly>`_.