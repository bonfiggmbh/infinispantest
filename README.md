# Infinispan Test

A small example project to evaluate an Infinispan cache with Wildfly and Arquillian.
 
The challenge has been providing the runtime dependencies for the Arquillian tests, as declaring them in the _META-INT/MANIFEST.MF_ was ignored. What worked is declaring the runtime dependencies in the _WEB-INF/jboss-deployment-structure.xml_.