# Random-User-API-Performance-Test

## Finding out actual TPS if 120000 users can give load for 12 hours. Load Test & Stress Test are performed 
on this URL: https://random-data-api.com/api/v2/users

## Performed Load Test:
1. Transaction per second: 2.77 tps
2. Needs to achieve 2.77 tps for 12 hrs according to the distributed load
3. If the server can handle 1 hr load for the distributed load and maintain 2.77 tps, it can handle 12 hrs as well.
4. Load test must be performed in non-gui mode.

## Performed Stress Test:
1. Transaction per second: 2.77 tps
2. Needs to find out the bottleneck point when the system starts to give an error.
3. In this scenario, time will be constant and load will be increased.
4. Stress test must be performed in non-gui mode.
   


<img width="613" alt="Load Test" src="https://github.com/litamouri/Random-User-API-Performance-Test/assets/106230174/d5318937-cc92-4386-aa25-b938f39373c7">


<img width="609" alt="Stress Test" src="https://github.com/litamouri/Random-User-API-Performance-Test/assets/106230174/b3daaa57-488d-408d-8896-0a44849279e7">
