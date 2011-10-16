Actandra
========

An activity stream implemented using Cassandra.
More of a proof-of-concept than anything production like. But it provides a good starting point for creating say a news feed similar to Facebook's.

Supports

  * Get an activity stream
  * Add an activity to an activity stream
  * Add/remove subscribers for a given stream
  * Post a comment to an activity

Have not been load tested at all but should in theory scale by adding more Cassandra nodes.
The library itself is stateless and can be run on as many machines as necessary.
Some terminology was inspired by the Activity Streams format (http://activitystrea.ms/)

So far very few lines of code, ~150 LOC.

Work in progress!
