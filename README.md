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
- AMF (Access and Mobility Management Function) :  {monility management , registration} , responsible for supporting the device to move between different radio cells , also responsible for establishing signaling encrypted connection to the device so the device can register itself and can get authenticated and ready to acess the internet
- AUSF (Authentication Server Function) : {security} supports AMF with authentication related function during different procedures
- UDM (Unified Data Management) : user subscription data is stored in user data repository (UDR) , UDM is the frontend for the user subscription data , the AMF dosnt contain user sub data , UMF supports AMF for registration of devices
- PCF (policy control function) : {session mgmt policies  , non-session policies , charging devices depending on usage of device
  
## 5G deployment options 

![Screenshot from 2023-11-02 21-37-55](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/d1e42d27-e05a-4a92-ac73-e90248156f78)

- EPC = evolved packet core (4G)

![Screenshot from 2023-11-02 21-38-58](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/6e324445-3b0a-4176-9044-9add401c121d)

![Screenshot from 2023-11-02 21-39-50](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/2a255d41-27b3-4b3e-b03d-23ebd7745bd0)

- option 3 : core network sends data to 4G base staion and it splits data streams , part of which is sent to UE and other half sent to gnode b which is then sent to UE  ; eNode B can send smaller data rate rest can be forwarded to gNodeB and gNodeB can transmit with higher data rates
- option 3a : data directly sent from core network to gNodeB ; disadvantage :- data cannot be sent over both gNOdeB and eNodeB for ex :- for eMBB the data rates needs to be higher so they can be sent directly from core network to gNodeB and then to UE , on the other hand if there is a need for voice over LTE that can be sent to eNodeB then to the network  no need for gNodeB as voice over LTE needs low data rates
- option 3x : combination of 3 and 3a

 ![Screenshot from 2023-11-02 21-51-42](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/18882cf3-3b37-49b1-8fef-bd3b09a3cd55)

![Screenshot from 2023-11-02 21-52-10](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/099f1451-7226-4067-aa0a-cb4fa6337966)

![Screenshot from 2023-11-02 21-52-30](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/d9cab915-5ed3-4061-a0ea-574b79197077)

![Screenshot from 2023-11-02 21-53-23](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/e1fa5d10-fa23-4d3c-a22a-fd43ce7acf5c)

![Screenshot from 2023-11-02 21-53-51](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/54e5af91-b60b-48b6-978d-e6fc8de0d12b)

## RAN PROTOCOL STACK

![Screenshot from 2023-11-02 22-35-57](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/52265c6d-869e-4c08-aa13-611e34ee49a0)

- user plane protocol stack : supports carrying user data between different application in the ue and in the network
- control plane protocol stack : can be seen as carrying the control info between the UE and the gNodeB or the core network

### user plane protocol stack : 
![Screenshot from 2023-11-02 22-38-28](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/7eccdd3a-ba0c-4bc9-9b3b-af1411a11d32)

- PHY : efficient wireless communication , bits and bytes transmitted in wireless channels
- MAC : retransmission (looking for errors) , multiplexing.demultiplexing ,  scheduling
- RLC : robust error detection scheme ARQ , packets broken down into smaller packets called segmentation , puts them back together in reassembling side
- PDCP : ip header compression ; ciphering and integrity protection of info so no one can eaves drop ; duplicate removal
- SDAP : Mapping the QoS bearer into the right radio bearer according to the QoS requirements

![Screenshot from 2023-11-02 22-46-38](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/14c0077d-d151-4308-9762-dcb658f0adfc)

![Screenshot from 2023-11-02 22-47-20](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/d28794c9-f552-4558-9229-6f597e8bc176)

![Screenshot from 2023-11-02 22-47-43](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/7032593c-ca57-454c-b7bd-77874cb89f87)

- NAS (NON-ACCESS STRATUM) : (core network <==> UE) authentication , security ,idle mode procedure
- RRC (RADIO RESOURCE CONTROL) : (RRC gNodeB <==> RRC UE) responsible for RAN related control plane procedures like broadcasting systum info which helps the device learn the essential parameters of the cell , responsible for setting up radio bearers , 


## SERVICE DATA ADAPTATION PROTOCOL (SDAP) 

![Screenshot from 2023-11-02 23-40-40](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/b8b8738b-992d-4e26-bb16-3a12dbb2ff81)

- QoS : ability to provide different priority to different application , users or data flows or to guarantee a certain level of performace
- Qos flows : QFI : packets are classified and marked using an ID called QOS identifier or QFI ; using these packets with certain QFI can recieve cooresponding treatment used to differentiate package from different kinds of services  

![Screenshot from 2023-11-02 23-45-10](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/6a0b9b96-9b17-4d88-8129-0c8887cfe7d9)

![Screenshot from 2023-11-02 23-45-27](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/1f69ecc5-0fab-40c7-83ec-5ed5de110841)

- guarenteed bitrate (GBR) QoS flow : voice comm requires GBR so voice doesnt get disrupted
- non guarenteed bitrate (NON-GBR) : used for busty traffic for ex browsing the net or downloading a file
- delay critical : mission critical application ex self driving cars robots etc

![Screenshot from 2023-11-02 23-48-39](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/a221bf60-8807-4ea2-8353-58bb025e6cf0)

![Screenshot from 2023-11-02 23-49-11](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/c81a0ecc-1fec-4a18-9f41-ad144751562e)

![Screenshot from 2023-11-02 23-50-26](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/34828365-3076-4106-bf92-54aa15e0d9dd)

![Screenshot from 2023-11-02 23-50-48](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/c1d8cc3f-237f-4639-99c4-d5f8983f7ebf)

- reflecive mapping : when device uses same QoS flow and radio bearer in uplink as in downlink
- explicit mapping : when device configured to use a specific QoS flow and bearer through RRC signals then it is called explicit mapping

![Screenshot from 2023-11-02 23-53-20](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/1554b80a-e6f1-48fc-b540-7f8b9b59dfaa)











