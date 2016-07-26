sbteclipse
==========

Productivity fork of https://github.com/typesafehub/sbteclipse 

Plugin for sbt to create Eclipse project definitions. Information about project can be found in original repo.

Modifications
=============
Workaround for issues with eclipse output directory and project naming when managing subprojects.

Usage
=====

resolvers += Resolver.url("michae1T Repo", url("https://dl.bintray.com/michae1t/maven"))(Resolver.ivyStylePatterns)

addSbtPlugin("com.typesafe.sbteclipse" % "sbteclipse-plugin" % "5.0.0")


