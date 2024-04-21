# Random-user-API-performance-testing
 In this repository, API performance is tested with multiple users.
## Finding out actual TPS if 120000 users can give load for 12 hours. Load Test & Stress Test are performed.
 on this URL: https://random-data-api.com/api/v2/users

# Performed Load Testing:
* Transaction per second: 2.77 TPS
* Needs to achieve 2.77 TPS for 12 hrs according to the distributed load
* If the server can handle 1 hr load for the distributed load and maintain 2.77 tps, it can handle 12 hrs as well.
* Load test must be performed in non-gui mode.
  <img width="613" alt="Load Test" src="https://github.com/paularpi66/Random-user-API-performance-testing/assets/72724463/1df0861b-fae6-49f7-a812-8020c78bc6ba">

# Performed Stress Test:
* Transaction per second: 2.77 TPS
* Needs to find out the bottleneck point when the system starts to give an error.
* In this scenario, time will be constant and load will be increased.
* Stress test must be performed in non-gui mode.
  <img width="609" alt="Stress Test" src="https://github.com/paularpi66/Random-user-API-performance-testing/assets/72724463/cb389ab8-5c25-4b0f-8030-5db111ff8804">


