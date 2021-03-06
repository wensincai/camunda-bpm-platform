This is a distribution of Camunda BPM platform v${project.version} (visit
http://docs.camunda.org/) a dual-license Java-based framework. This particular
copy of the software is released either under the Apache License 2.0 (Community
Platform) OR a commercial license agreement (Enterprise Platform).

License information can be found in the LICENSE file.
 
The packaged Wildfly Application Server is licensed under
the LGPL license.

==================

Contents:

  lib/
        This directory contains the java libraries for application 
        development.

  modules/
        This directory contains additional modules for Wildfly Application
        Server. You can use these modules to patch a vanilla distribution
        of Wildfly Application Server.

  server/
        This directory contains a preconfigured distribution 
        of Wildfly Application Server with Camunda BPM platform readily
        installed.

        run the
          server/wildfly-${version.wildfly10}/bin/standalone.{bat/sh}
        script to start up the the server.

        After starting the server, you can access the 
        following web applications:

        http://localhost:8080/camunda
        http://localhost:8080/engine-rest

    sql/
        This directory contains the create and upgrade sql script
        for the different databases.
        The engine create script contain the engine and history tables.

        Execute the current upgrade script to make the database compatible
        with the newest Camunda BPM platform release.

==================

Camunda BPM platform version: ${project.version}
Wildfly Application Server version: ${version.wildfly10}

=================
