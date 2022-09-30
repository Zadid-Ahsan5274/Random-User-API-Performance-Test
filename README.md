# Random-User-API-Performance-Test

## Tools and Technologies Used
- Java
- Apache Jmeter 5.5

## Scenario of this project
Performance test for the given API. User will hit the server for a certain amount of time. 
- **Load Test:** Actual throughput/TPS is calculated depending on the certain number of user hitting the server with increasing time. 
Based on giving condition, the actual throughput does not match with the expectation.
- **Stress Test:** Within the same time, an increasing number of users hitting the server, thus 
increasing load. At a certain point of time and user, system starts to show error which is the stress test point.

## How to run this project
- Clone this project
- Open jmeter and from file menu open the jmx file
- Run a single test at a time and keep other tests disabled

## Prerequisites
You must have installed JDK(LTS version e.g. 8 or 11) to run this project

## Load Test Strategy Snapshots
![Screenshot 2022-09-29 145149](https://user-images.githubusercontent.com/82231014/193291794-57ab9b4a-475f-41a4-b2d9-5e6c0f74c2e1.png)
![Screenshot 2022-09-30 194859](https://user-images.githubusercontent.com/82231014/193291803-3006d432-06b3-4feb-aa74-74710879c07b.png)
![Screenshot 2022-09-30 194913](https://user-images.githubusercontent.com/82231014/193291820-92df1f02-e524-416b-ac1c-baed05ecf69b.png)

## Test Output
![Screenshot 2022-09-29 140059](https://user-images.githubusercontent.com/82231014/193291881-5a1ec3ac-b99c-436e-95e4-7ee077d35dbe.png)
![Screenshot 2022-09-29 144250](https://user-images.githubusercontent.com/82231014/193291901-dededd50-cb8d-488c-957b-a474cf2e5caf.png)
![Screenshot 2022-09-30 193906](https://user-images.githubusercontent.com/82231014/193291914-f119e470-bc73-4f73-bc75-4f1df12f3565.png)

