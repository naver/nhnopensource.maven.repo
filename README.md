nhnopensource maven repo
==============
 
 To use this maven repo, you need to add this line into your project's pom

    <repositories>
        <repository>
  	        <id>ngrinder-core</id>
  	        <url>https://github.com/nhnopensource/nhnopensource.maven.repo/raw/master/{releases/snapshots}</url>
  	    </repository>
  	</repositories>

 Just append snapshots or releases to that root URL, as appropriate for your project’s dependencies.
