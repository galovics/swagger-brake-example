# Swagger Brake plugin examples
This repository contains 2 projects as a showcase for using the Maven and Gradle plugins
of Swagger Brake.

Both examples are building on the fact that you are running an Artifactory server locally 
(this can be adjusted in the configuration anytime) which has a snapshot repository available
called `libs-snapshot-local`. The easiest way to set up a local Artifactory server is by using Docker.

Please refer to the [documentation](https://www.jfrog.com/confluence/display/RTF/Installing+with+Docker) for starting the server.

Example command as a starting point:
```bash
docker run --name artifactory -d -p 8081:8081 docker.bintray.io/jfrog/artifactory-oss:latest
```

Now you should be able to build both projects successfully.

The main component of Swagger Brake can be found [here](https://github.com/redskap/swagger-brake).

The Maven plugin repository can be found [here](https://github.com/redskap/swagger-brake-maven-plugin).

The Gradle plugin repository can be found [here](https://github.com/redskap/swagger-brake-gradle).

## License
```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```