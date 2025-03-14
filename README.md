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

![LX](https://github.com/user-attachments/assets/4735f08d-01b4-4079-8075-ab86767b598b)

## This is Load test Step Report 
- for 5 minutes

![5min](https://github.com/user-attachments/assets/5578febc-6bc9-4e32-810b-99a526eba2a5)

- for 10 minutes
  
![10min](https://github.com/user-attachments/assets/5b1cdbec-8529-4fcd-b7ec-d405a5272a0b)

- html report for 20 minutes and the error rate is 0.05%
  
![loadtest](https://github.com/user-attachments/assets/4f709b20-25aa-41fb-8f80-caff34bda6c9)

## Stress Report Analysis
After pass the load test we conduct the stress testing starting from 20 minuntes and inceasing the user to find the capacity point and bottleneck.

### Conducted tests until find the bottleneck:
- 20-minute load test for 7500 users
- 20-minute load test for 9000 users
- 20-minute load test for 12000 users

## This is Stress test  Excel file

![SX](https://github.com/user-attachments/assets/7a39c08a-549c-485d-bf9e-8ae40bfe2a2d)

## html report for Stress testing

![12KuSER](https://github.com/user-attachments/assets/a185cfd1-e69c-4821-ab38-b169b4c5f365)



# For Question-2
# Demoney Test Case
## Report summary for deposit

![depo](https://github.com/user-attachments/assets/e20bf174-265c-4b70-9e79-5407185ec00b)

## Report summary for sendmoney

![SM](https://github.com/user-attachments/assets/4a40c5be-ac59-435f-a41b-2f875f36d940)

## Report summary for paymeny

![pay](https://github.com/user-attachments/assets/e3a7cce5-fb23-4784-a9c3-b8c64c3554ec)

## HTML Report for Demoney

![demoney](https://github.com/user-attachments/assets/1189a8c6-2362-4f45-a69f-2e38362ed08a)









