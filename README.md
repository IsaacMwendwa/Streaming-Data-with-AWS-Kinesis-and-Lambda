# Streaming Data with AWS Kinesis and Lambda

## Introduction
* There are two main ways of working with data - batch or stream. Neither is better or worse - they're just different tools for different jobs. A data engineer understands the business need and finds the right solution: 
    ![image](https://github.com/IsaacMwendwa/Streaming-Data-with-AWS-Kinesis-and-Lambda/assets/51324520/8bfc2a14-4dc8-4ef0-8283-ff86a5fd8634)

### Problem Definition
We will be helping Cody, the Sustainability Manager for the City of San Diego. As the city's Data Engineer, you will be helping Cody decrease emissions and accidents using the internet of things or IOT. She wants to put a sensor in each vehicle that will transmit emissions, time and speed for that vehicle. This is known as *vehicle telematics*, a common streaming data use case

  * ![image](https://github.com/IsaacMwendwa/Streaming-Data-with-AWS-Kinesis-and-Lambda/assets/51324520/60dc84c9-2719-4256-bfcd-b0ace3dea90b)

### AWS Technologies Employed
* AWS Kinesis has Data Firehose, Data Streams and Data Analytics as sub-services. You'll be combining these to solve streaming data use cases. Let's start with Firehose.
    ![image](https://github.com/IsaacMwendwa/Streaming-Data-with-AWS-Kinesis-and-Lambda/assets/51324520/3408f20b-0e23-4a13-a04a-77ceecc95ab0)
  
* Data Firehose Sub-service has the Firehorse Delivery Stream (FDS) as the key component. The FDS consists of a "Producer" - the data generator of a Firehose stream, and a "Destination" - where the data gets stored:
    ![image](https://github.com/IsaacMwendwa/Streaming-Data-with-AWS-Kinesis-and-Lambda/assets/51324520/ab55ca16-6696-4674-bf11-cf678878df6a)
  
* To create a Firehose client:
    ![image](https://github.com/IsaacMwendwa/Streaming-Data-with-AWS-Kinesis-and-Lambda/assets/51324520/ca876111-4299-49c5-9dc5-fe96877eb331)
  
* Working with delivery streams:
    ![image](https://github.com/IsaacMwendwa/Streaming-Data-with-AWS-Kinesis-and-Lambda/assets/51324520/6b53e0b0-bdcc-4bbf-be2a-cc9650536a46)
  
* Deleting redundant streams:
    ![image](https://github.com/IsaacMwendwa/Streaming-Data-with-AWS-Kinesis-and-Lambda/assets/51324520/d7677025-c2ae-4f46-a8b7-d29646cf65fc)





