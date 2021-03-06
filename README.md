# Graph for Scala
Graph for Scala is intended to provide basic graph functionality seamlessly 
fitting into the Scala Collection Library. Like the well known members of 
`scala.collection`, Graph for Scala is an in-memory graph library aiming at 
editing and traversing graphs, finding cycles etc. in a user-friendly way. 
Besides ready-to-go implementations of JSON-Import/-Export and Dot-Export, 
more popular graph formats, mirroring of graph databases as well as distributed 
processing are due to be supported.

Graph for Scala was originally planned to be moved from Assembla to the Scala Extended 
Core Library, a new facility to be launched sometime later by the Scala Core Team. 
Until then, use
[Graph for Scala on Assembla](https://www.assembla.com/spaces/scala-graph/documents)
along with this repository.

To download the latest release `1.6.1` of the core module, SBT users will have to add

```
libraryDependencies += "com.assembla.scala-incubator" % "graph-core_2.10" % "1.6.1"
```

As a Maven user, please set  
```
group id: com.assembla.scala-incubator  
artifact id: graph-core_2.10  
version: 1.6.1  
```

For a direct download you may select the required artifacts including the executable JARs,
Scaladoc and sources [here](https://oss.sonatype.org/content/repositories/releases/com/assembla/scala-incubator/).

You may also browse Scaladoc online at
[Core API](http://www.scala-graph.org/api/core/api/#scalax.collection.package),
[Constrained API](http://www.scala-graph.org/api/constrained/api/#scalax.collection.constrained.package),
[Dot API](http://www.scala-graph.org/api/dot/api/#scalax.collection.io.dot.package) and
[JSON API](http://www.scala-graph.org/api/json/api/#scalax.collection.io.json.package).

Any [feedback](https://groups.google.com/forum/#!forum/scala-graph) is appreciated.
You are also welcome as a co-contributor.

Have fun with Graph for Scala.

Peter