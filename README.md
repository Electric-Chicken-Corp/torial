torial
======

Interactive web-based scientific computing tutorial 

### possible way forward
1. go to website, type in {username, passwd, session-type} (this can be a script for the first attempt)
2. lauch docker instance of the specified session-type with user and passwd created and return the docker container-id
3. server gets container-id from 2, and uses wetty to launch the instance (docker exec -it [container-id] bash)
