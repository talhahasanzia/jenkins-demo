# jenkins-demo app for CI 


- Write configurations for different stages. For different flavours in different environments. 
- Run automated tests before build is made.
- Automate process of this test-> build for each development cycle.
- CI pulls source from git/scm, once the code is pushed.
- Defince rules for passing build, like, code quality, automation tests, once the processes go through happy flow, make a build snapshot.
- build - test -vrify - release

## Cycle

                                Pass-> Package -> SQA -> Release
                               /
Compile -> Build -> Unit Test <
                               \ Fail-> Reject build
                                
                                
## Plugins
Use Jenkins Plugins for acheiving tasks that satisfy your conditions during build process.

