# JMeter Performance Testing
## Project Overview
This project contains JMeter performance test collections for two scenarios:
### Load Test & Throughput Analysis
- Limited the test duration to a maximum of 20 minutes.
- Verified whether the server can handle the expected load.
## Performance Testing for Booking API
In the scenario Total user: 120000 and Time Period: 12 hours = 12 * 60 * 60 seconds = 43,200 seconds
Throughput (Requests per Second): 120,000 users / 43,200 seconds ≈ 2.78 requests/second
##### Conducted tests in 3 steps:
- 5-minute load test
- 10-minute load test
- 20-minute load test


## This is Load test Excel file


![l1](https://github.com/user-attachments/assets/fe649776-9fb1-469f-815f-3c569d509f32)

## This is Load test Step Report 
- For 5 minutes

![5min](https://github.com/user-attachments/assets/5578febc-6bc9-4e32-810b-99a526eba2a5)

- For 10 minutes
  
![10min](https://github.com/user-attachments/assets/31183925-8178-46e0-912b-2dcac575df22)

-  For 20 minutes and the HTML report
  
![loadtest](https://github.com/user-attachments/assets/4f709b20-25aa-41fb-8f80-caff34bda6c9)

## Stress Report Analysis
After pass the load test we conduct the stress testing starting from 20 minuntes and inceasing the user to find the capacity point and bottleneck.

### Conducted tests until find the bottleneck:
- 20-minute load test for 7500 users
- 20-minute load test for 9000 users
- 20-minute load test for 12000 users

## This is Stress test  Excel file

##  Summary report 20-minute load test for 7500 users

![7500](https://github.com/user-attachments/assets/8cc7ed1a-5ece-4881-8831-b52fc4898201)

##  Summary report 20-minute load test for 9000 users

![9000](https://github.com/user-attachments/assets/ba3d1072-c96c-4375-8dda-554796b8ab3e)

##  Summary report 20-minute load test for 12000 users

![12000](https://github.com/user-attachments/assets/a566c9e7-832a-4c01-9fa7-66dd173f8e1f)


## html report for Stress testing 18000 user

![l2](https://github.com/user-attachments/assets/5eaa1ccb-191b-4bc1-b815-5523d3bce3bf)

## load test and stress test from excel file

[booking-api-test-report.xlsx](https://github.com/user-attachments/files/19259508/booking-api-test-report.xlsx)


# For Question-2
## Demoney Test Case
### Report summary for deposit

![depo](https://github.com/user-attachments/assets/e20bf174-265c-4b70-9e79-5407185ec00b)

## Report summary for sendmoney

![SM](https://github.com/user-attachments/assets/4a40c5be-ac59-435f-a41b-2f875f36d940)

## Report summary for paymeny

![pay](https://github.com/user-attachments/assets/e3a7cce5-fb23-4784-a9c3-b8c64c3554ec)

## HTML Report for Demoney

![demoney](https://github.com/user-attachments/assets/1189a8c6-2362-4f45-a69f-2e38362ed08a)









