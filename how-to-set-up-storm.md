How to run storm

refer to this article: http://www.haroldnguyen.com/blog/2015/01/setting-up-storm-and-running-your-first-topology/
set path: http://stackoverflow.com/questions/20793737/how-can-i-add-storm-in-my-path/20794351
make sure storm.yaml file is configured properly

steps to start
1. zkServer run
2. storm nimbus
3. storm supervisor
4. storm ui
5. storm jar /Users/vivian/apache-storm-0.9.2-incubating/examples/storm-starter/target/storm-starter-0.9.2-incubating-jar-with-dependencies.jar storm.starter.ExclamationTopology <name of topology>

if anything is not working as it so, check the log files.
they are in conf folder
