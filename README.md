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

# 5G NEW RADIO (NR) RADIO AREA NETWORKA

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
### control plane protocol stack
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

## PACKET DATA CONVERGENCE PROTOCOL (PDCP)
![Screenshot from 2023-11-03 09-55-26](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/e2bee4fb-001a-4cdc-9a63-4b1c1b751be6)

![Screenshot from 2023-11-03 09-56-04](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/b7dcf8fb-2c84-48e2-be30-faf71557d4d9)

- For small data packets (voice packets) the header itself would be as long as the data packet .
- PDCP performs header compression to reduce header length to a couple of bytes for wireless trasmission
- Decompression of header size before it is transmitted over IP protocols in the wired network is also done by PDCP
- The header compression scheme is based on robust header compression (ROHC) protocol

![Screenshot from 2023-11-03 10-00-24-1](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/26a5f704-87c2-4bda-a9cb-d6d432770d4f)

- taking unencrypted data and encrypting it into cypher text using an encryption key

![Screenshot from 2023-11-03 10-01-47](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/aab29105-151c-4afb-a7fb-14d46cee6bda)

- To achieve more data rate , duplication can be used to send the exact same data through two different radio bearers to improve reliability.
- This way even if one fails , UE can recieve data from the other bearer
- In recieving side PDCP is responsible for discarding the duplicates and picking the anaronious packet { called selection diversity } if there is an error in one of the radio bearers

![Screenshot from 2023-11-03 10-06-38](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/69fc447d-2b02-4ce8-b093-4c899e1129ec)

- PDCP acts as sequence number to ensure in-sequence delivery

## RLC { RADIO LINK CONTROL } 

![Screenshot from 2023-11-03 19-15-22](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/2cab9ff5-9299-4b80-a0f6-281dc4871089)

### RLC MODES

![Screenshot from 2023-11-03 19-16-07](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/48bb18c8-e997-4937-9d1d-1cb2c37f5194)

- transport mode : in these cases the channels are already designed in such a way that there is no need for segmentation
- acknowlaged mode : essential for web browsing , file transfer etc.

### segmentation

![Screenshot from 2023-11-03 19-19-05](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/6ec9a131-c28b-47cd-9757-a483c50e6cba)

- RLU PDU's are assembled as soon as possible without waiting and the MAC layer performers the concatination depending on the trasfered larger size { benefits in low latency applications }


### retransmissions 

![Screenshot from 2023-11-03 19-22-09](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/71e1171d-155f-4329-907c-d875303a1023)

- IN-SEQUENCE delivery not handled in RLC { done by PDCP , also optional }
  - reduce the overall latency of later packets , do not have to wait for retransmission of an earlier missing packet and it an be delivered directly to higher layers  

![Screenshot from 2023-11-03 19-25-30](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/0e040a5a-963e-4747-a694-7272b02d8c06)

![Screenshot from 2023-11-03 19-25-51](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/d82562ce-d049-482d-9176-9594bb78c699)

![Screenshot from 2023-11-03 19-26-18](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/c9e67f9c-603d-4810-b374-cc52b994249b)

![Screenshot from 2023-11-03 19-26-36](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/242d8145-387a-42ae-9651-1ad073efa149)

![Screenshot from 2023-11-03 19-26-50](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/3f39ff5b-08c6-425b-bc44-889401eede10)

![Screenshot from 2023-11-03 19-27-17](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/aa91657b-88e5-41de-a291-b63540b72315)

![Screenshot from 2023-11-03 19-27-45](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/cc0bb6a5-b09f-4b68-b494-ad5048651f2f)

## MAC (MEDIUM ACCESS CONTROL) 

![Screenshot from 2023-11-03 19-58-37](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/6f646a9e-1de2-4298-92d1-e642b66117cc)

![Screenshot from 2023-11-03 19-59-33](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/bdfd5049-ae86-45d6-ac93-5286df735874)

- MAC provides services to RLC trough logical channels
- MAC layer uses services from physical layer in the form of transport layer

![Screenshot from 2023-11-03 19-59-50](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/ca86c645-31ef-4f90-b8e7-487a6c283d07)

- logical channel : is defined by the type of information it carries and generally classified as a control channel used for transmission of control and config information necessary for operating an NR system or as a traffic channel used for the user data .
- transfer channel : defined by how and what characteristics the information is transmitted over the radio interface

![Screenshot from 2023-11-03 20-06-41](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/b1decf73-ed14-490d-a68c-161b30c44412)

![Screenshot from 2023-11-03 20-06-56](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/1078872a-8de4-4fd8-9e08-7eb8d8ff4d5b)

![Screenshot from 2023-11-03 20-07-19](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/292a9c68-a437-4713-a292-b8152ae161fa)

![Screenshot from 2023-11-03 20-07-36](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/40502c9a-c987-47a1-973a-700d50d55035)

![Screenshot from 2023-11-03 20-07-53](https://github.com/KRIISHSHARMA/RESEARCH/assets/86760658/1863b917-280a-40cd-a5b9-d713e408d62b)

- only the code block group that is affected by the error is transmitted





















