# ReqRes API Performance Test Report

## Test Configuration

Target URL:
https://reqres.in/api/users?page=1

Method:
GET

Concurrent Users:
50

Duration:
2 Minutes

Tool:
Apache JMeter

---

## Test Results

Total Requests:
68,993

Average Response Time:
82 ms

Minimum Response Time:
56 ms

Maximum Response Time:
137 ms

90th Percentile (p90):
573.83 ms

95th Percentile (p95):
647.61 ms

Throughput:
119.36 requests/second

Failed Requests:
616

Error Rate:
0.89%

---

## Observation

The API handled 68,993 requests during the 2-minute test with 50 concurrent users.

The average response time was 82 ms, indicating fast response processing. The throughput achieved was approximately 119 requests per second.

The error rate remained below 1%, with around 616 failed requests. Most requests completed successfully, and the p90 and p95 response times were below 650 ms, demonstrating consistent performance for the majority of users.

---

## Conclusion

The ReqRes API showed stable performance under the configured load. Response times were low, throughput was consistent, and the error rate was minimal. Overall, the application handled 50 concurrent users efficiently during the 2-minute load test.