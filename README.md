# 5G system 

## system standardization 
- diffrent countries have different types of oulets disadvantage is that is expensive to maintain so many devices
- it would be much easier if design is based on one cooperative effort

  ![Screenshot from 2023-11-02 18-13-26](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/4babd333-4cd2-4f20-bdc0-1d6bb0c63c09)

- same issue for telecommunication
- if every country will have a diff technology for telecommunications then we will have many diff techonolies therefore no global interconnection and more expensive
- this is where ITU comes in
### ITU 

![Screenshot from 2023-11-02 18-20-11](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/23791748-9bbc-4882-8395-1a3427b8da17)

- (ITU-T) : is responsible for telecomm standardization ; coordinate different 
standards for telecomm and information technology ex : cyber security , machine learning etc
- (ITC-R) : responsible for radio communication , important when it comes to 5G ; have a role in managing how the international radio freq spectrum and satellite orbitory resources are used
- (ITU-D) : responsible for international telecomm development sector . responsible for creating policies and regulations and providing education on the topic of telecomm to developing nations

### 5G REQUIREMENTS 

![Screenshot from 2023-11-02 18-21-21](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/5f05a11c-3aab-443a-8cff-f323876fce03)

### 3GPP

![Screenshot from 2023-11-02 19-10-12](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/dc32bab4-89e8-4aa0-bcb1-48b402aa6363)

![Screenshot from 2023-11-02 19-10-59](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/c567aa32-9188-4e23-9b33-df028a88092c)

- TSG RAN : takes care of all the topics related to wireless comm
- TSG CT (core network and terminal) :  takes care of monitoring/security etc
- TSG SA (service su=ystem aspect) : management

                                                                                                      
 ![Screenshot from 2023-11-02 19-13-38](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/04d7adac-4550-477d-997e-6b3642b28718)

### 3GPP RELEASES TIMELINE 

![Screenshot from 2023-11-02 19-14-34](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/e8ceb983-aeff-47ad-9996-e7a5b68cb9df)

## 5G USE CASES

![Screenshot from 2023-11-02 19-35-36](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/7fe37de8-ac5c-49a3-a1a0-41b8c06db417)

![Screenshot from 2023-11-02 19-36-07](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/c0eed079-9053-4f00-a67c-0068328bd7b3)

![Screenshot from 2023-11-02 19-36-26](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/bfbb9357-aef0-49c1-aa49-7141afcbdca4)

![Screenshot from 2023-11-02 19-36-49](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/27a8013e-2e9b-44fd-8330-8d0d53a017d2)

![Screenshot from 2023-11-02 19-37-37](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/006d309e-a6f6-4bd1-89ae-ee410d949864)

## OVERVIEW OF 5G SYSTEM 

![Screenshot from 2023-11-02 20-38-20](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/13c3098e-8139-4ba6-9991-d7ab2c9a4ee8)
- independent scaling ( for different use cases )
- flexible deployment ( for diff performance ex eMBB , URLLC )
- seperating user plane and control plane also helps us achieve low latency because we can optimizing network deployment according to latency requirement.
### KEY NETWORK FUNCTIONS
- basesrtation : gNode B / Ng-eNB ( LTE+NG )
- UPF (User Plane Function) : {mobility anchor , policy enforcement . lawful interception} , provides interface to intent to make sure the devices does not exceed the amount of data that the user have in their subsciption
- SMF (session management function) : before the device tasmits the data the network needs to establish a new session , give the device an IP address and release the sesssion when device has finished its activity . AMF forwardsall session related messages to SMF
- AMF (Access and Mobility Management Function) :  {monility management , registration} , responsible for supporting the device to move between different rasio cells , also responsible for establishing signaling encrypted connection to the device so the device can register itself and can get authenticated and ready to acess the internet
- AUSF (Authentication Server Function) : {security} supports AMF with authentication related function during different procedures
- UDM (Unified Data Management) : user subscriber is stored in user data repository (UDR) , UDM is the frontend for the user subscription data , the AMF dosnt contain user sub data , UMF supports AMF for registration of devices
- PCF (policy control function) : {session mgmt policies  , non-session policies , charging devices depending on usage of device
-  
