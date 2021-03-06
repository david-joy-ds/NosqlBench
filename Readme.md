### Objective: 
To help users with NosqlBench adoption and to improve, make efficient the dev and production DSE stress testing, thereby, accelerating testing cycles and go to production timelines. 

### What is NosqlBench ? 
NoSQLBench is a performance testing tool for the NoSQL ecosystem. It brings together features and capabilities that are not found in any other tool.

You can run common testing workloads directly from the command line. 
You can generate virtual data sets of arbitrary size, with deterministic data and statistically shaped values.
You can design custom workloads that emulate your application, contained in a single file, based on statement templates - no IDE or coding required.
You can immediately plot your results in a docker and grafana stack on Linux with a single command line option.
When needed, you can open the access panels and rewire the runtime behavior of NoSQLBench to do advanced testing, including a full scripting environment with Javascript.
CQL Support is built into the tool, however, it is more like a machine harness so others can write their own clients for other system’s. 

### Origins & Current State: 
The building blocks of this project are rooted in procedural data generation capability was known before as 'Virtual Data Set' and a core runtime and scripting harness called ‘Engine Block’ project. The CQL piece was built and supported within DataStax and battle tested. 

In March of 2020, DataStax and the project maintainers open sourced this project, and was renamed to nosqlbench.io. More information on this link.
