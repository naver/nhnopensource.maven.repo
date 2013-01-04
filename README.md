 This is nGrinder jars on github
 ==============
We have created nGrinder jars repository on github.

To use nGrinder released jars you will need to add this line into your project's pom

    <repositories>
        <repository>
  	        <id>ngrinder-core</id>
  	        <url>https://github.com/nhnopensource/nhnopensource.maven.repo/raw/master/{releases/snupshots}</url>
  	    </repository>
  	</repositories>

 Just append snapshots or releases to that root URL, as appropriate for your project’s dependencies.
