In this exercise, you need to develop a containerized application and deploy it. The web application shows to the end user an "hello world" landing page along with your name, retrieved from a database.

The exercise must met the following acceptance criteria (the more, the merrier):

1. Front end
    - A web server that displays an "hello world, {name}" page with the {name} token should be replaced with a value taken from the database
    - Dockerfile to build the front end container
2. Database
    - A database with a simple schema containing a table with a row having at least a "name" column and a row with your name on it.
    - Dockerfile to build the database container
3. Use one of the following container orchestration approaches:
    - docker-compose
    - kubernetes yaml
    - helm
    - kustomize
4. README file with list of instructions to build and run the proposed solution

Rules:
1. Copy and paste from other sources is permitted, we only require reference to it in the README
2. All resources required to build/run your solution should be provided
3. All programming/scripting languages are allowed (e.g. python,javascript,java,go,bash,c++,C#)
4. You must choose a database type that doesn't require a commercial license for development and runs on containers
5. We also accept partial solutions

What we look for:
1. Can follow the instructions you provide to build and run the solution in the README.md
2. Can build Docker images
3. Can apply the container orchestration configuration
4. Can connect to front end application with a web browser and see "hello world, {name}" message

Bonus points:
1. Code quality (testing/linting etc.)
2. Build scripts (e.g. bash, makefile, gradle)
3. Approach to configuration values (e.g. secret management)
4. Recorded general considerations in the README.md (e.g. security aspects)

