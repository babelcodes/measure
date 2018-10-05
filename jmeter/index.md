# JMeter

## Concepts

- A __Test Plan__ contains:
   - __User Defined Variables__
   - __Thread Group__ that defines:
      - Count of simultenous connections, by using _User Defined Variables_
      - _Samplers__ as __HTTP Request__ to test an URL
         - You can use slugs from files to customize URLS: `/${__StringFromFile(C://dev//spikes//jmeter//data//slugs.txt)}` in `Path` field. See [Apache JMeter - User's Manual: Functions and Variables](https://jmeter.apache.org/usermanual/functions.html#__StringFromFile)
   - __Listeners__ as __Aggregate Report__ and __View Results in Table__ to see results / measures

![Test Plan](images/jmeter-a-test-plan.png)
![Test Plan / Thread Group](images/jmeter-b-thread-group.png)
![Test Plan / Thread Group / Samplers / HTTP Request](images/jmeter-c-http-request.png)
![Test Plan / Listeners / Aggregate Report](images/jmeter-d-listeners-aggregate-report.png)
![Test Plan / Listeners / View Results in Table](images/jmeter-e-listeners-view-results-in-table.png)

## Resources

- [Apache JMeter - User's Manual: Getting Started](https://jmeter.apache.org/usermanual/get-started.html)
- [Mazira - Introduction to Load Balancing Using Node.js - Part 1](https://mazira.com/blog/introduction-load-balancing-nodejs)
- [Load Testing with JMeter: Part 1 - Getting Started | Lincoln Loop](https://lincolnloop.com/blog/2011/sep/21/load-testing-jmeter-part-1-getting-started/)
