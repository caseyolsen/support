Event Buffer subscription to MQTT broker
----------------------------------------

When a continuous stream of data is required for a pipeline, the data can be delivered to
Falkonry either through its `Event Buffer REST API <file:///Users/olsen/repos/support/docs/_build/html/integration/index.html#rest-api>`_
or through subscription of the event buffer to an MQTT broker. 

Simple properties of the subscription are specified when the MQTT broker is configured,
such as its URL, user name, and password. Falkonry treats the data transmission just like
if individual files are created.

Once a subscription is created, the event buffer will keep receiving 

.. raw:: html

   <iframe src="https://player.vimeo.com/video/178228914" width="500" height="281" frameborder="0" allowfullscreen=""></iframe>

