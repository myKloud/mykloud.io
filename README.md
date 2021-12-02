# myKloud (https://mykloud.io/)
## Introduction:
Billions of people take the internet for granted and never questioned what actually happens to their data on the internet and how the internet actually works. The internet we know today is centralized big companies developed many frameworks, mechanisms, and tracking tools to track everything we do online to sell ads, and that’s no secret. Which raised huge concerns around our data privacy a survey was conducted in Aug 2021 shows that 67% of Americans are concerned about their Data Privacy on the internet for more details, check Concerns around data privacy are rising, and blockchain is the solution (https://cointelegraph.com/news/concerns-around-data-privacy-are-rising-and-blockchain-is-the-solution). 

The original Internet’s plan was not to be centralized. In fact, it was a project by the *US DoD (Department of Defense)* to establish a computer data communications network that could withstand unforeseen events and disasters like war. Therefore it must be decentralized so that if one part of the system fails, the rest can still function and if you want to know more, check The Evolution of the Internet, From Decentralized to Centralized (https://hackernoon.com/the-evolution-of-the-internet-from-decentralized-to-centralized-3e2fa65898f5).

While many companies tried to develop tools and mechanisms to encrypt the data on transit and developed secured communications protocols such as HTTPS and SFTP, and others, that didn’t solve the problem since even if the data is protected on transit, the data will eventually get stored on a server somewhere, which means someone can access it if they really need to. and you can see that in email services such as Gmail. Gmail makes it clear that they are reading your email and do actions based on the content you have on your personal email. More details can be found on Google Will Keep Reading Your Emails, Just Not for Ads (https://variety.com/2017/digital/news/google-gmail-ads-emails-1202477321/). 

Okay, so given that we know that everything we do online is not really secured, some might argue, so what? I don’t have anything to hide anyway... really? What about your locations or the last places you were? Or about your private family pictures? What about your personal documents such as social security, passports/ids scans? What about your private conversions with family when Alexa or Siri is listing? 

Ok, if that’s a problem, what’s the solution then? The solution was, still, and will always be a decentralized internet. 

### Centralized vs. Decentralized:
To understand the difference, I’m going to share a straightforward example: sending letters from person A to person B. let’s say John wants to send a love letter to Sara. Suppose John sends that through USPS. John must go to the USPS office then hand it over to a person in the office, and they will verify the address (and can open it if they have to) then give it to the driver. The Driver will go to Sara’s address (The driver can open it as well) then Leaves it at Sara’s door. Luckily Sara will open it and read it immediately if she's home. But if she’s out, a neighbor might see the mail and open it and put it back till she's back home and actually reads the letter. this is how the Centralized internet works. The USPS of the internet is called ISP (Internet Service Provider), and the traffic goes between ISP's through connected networks. 

Now let’s apply the example on decentralized internet; John will call Sara and check if she’s home. Once she confirms, he goes to her place and hands it over to her. That’s called a peer-to-peer network which is the core concept of the decentralized internet. more details can be found in the appendix. 

As a result, myKloud found an opportunity to give people the right to control their privacy and control who can see their data without compromising the convenience of the existing tooling. 

### What’s myKloud?
The idea started when our founder Mohamed Kiswani wanted to save his newborn daughter's pictures, birth certificate, and other papers on the cloud. And he didn’t want these pictures or documents to be used or seen by anyone since they are very private; at the same time, he didn’t want to store them on USB or store them offline since he has the habit of losing USB’s and reformatting his laptop every year a solution was needed and that was the beginning of myKloud. 

myKloud is a Data Privacy platform built on top of a blockchain. It takes advantage of both worlds where it offers the same apps we used to use all the time, such as email, notes, photos, videos, and docs sharing with full control on who can see what. 

Given the platform is going to be very big and it will take multiple stages. we’re going to break down the delivery into 3 main phases.

#### Phase 1 MVP: 
myKloud core component is the infrastructure integration since we’re not planning to change the experience for the existing applications. what we’re offering is having the same experience with better and more secured storage layers leveraging blockchain technologies and to achieve that we choose to start with three main apps.

1. KMail: a decentralized email service with E2E encryption that can be used with existing email client and native mobile client 
2. KFiles: a decentralized storage service that can store photos, videos, files and docs in deventlized fashion
3. myKoud Platform: The core platform that manages the underlying integrations with decentralized networks
4. MVP Success criteria:
    1. KMail 
        1. Cloud based Decentralized Email service stores all the contents of decentralized networks (storage storj.io and sia networks)
        2. Supports exchange (activesync) protocol to support the existing mail clients (outlook and AppleMail)
        3. Web & Mobile native Clients 
        5. E2E encryption enabled by default
        6. SDK for integrations 
    2. KFiles
        1. Stroage API's to store, list, move and retierive any file from decentralized networks (storage storj.io and sia networks)
        2. Web interface to explore all the account files
        3. Desktio agent that sync a local folder with remote folder 
        4. Storage should Decentralized and each file should be broken down intro 80 cuncks stored on 80 different nodes


# Appendix:

## What Is a Centralized Network?
Centralized networks are built around a single, centralized server/master node, which handles all major data processing and stores data and user information that other users can access. Client nodes can be connected to the main server and submit data requests instead of performing them directly. The majority of web services — including YouTube, a mobile app store, or your online banking account — are coordinated by a centralized network owner, meaning that all data transactions within these networks require verification via a third-party authority. As a result, centralized networks are currently the most widely used type of network on the web. However, these networks are dependent on a central network owner to connect all the other satellite users and devices — which means there is a single point of failure that malicious actors can deliberately exploit.
### Advantages*
    1. Simple, rapid deployment: Since command chains are clearly defined within centralized networks, delegation within the network is relatively simple, and less cross-chatter is required within different authorization levels. It’s also easy to add and remove client nodes from the network by creating or removing connections between the client node and the main server. However, this does not increase the network’s computing power.
    2. Affordable maintenance: Centralized networks are typically the most cost-effective options for small systems and require fewer resources to set up and maintain. Furthermore, when a network administrator needs to patch or update the network, only the central server must be updated. This reduces the time and overhead necessary to keep a network up to date.
    3. Consistency: Given the top-down nature of centralized networks, it’s easier to standardize interactions between the main server and client nodes. That can lead to a more consistent and streamlined end-user experience. Furthermore, since it’s relatively easy to track and collect data across the network, extraneous or deviant activity can be rooted out and removed following its priorities and needs.
## Disadvantages
    1. Increased downtime risks: Since centralized networks have a single point of failure, the entire network will likely shut down if the main server crashes. Therefore, client nodes will not be able to send, receive, or process user requests on their own. Furthermore, server maintenance may involve temporarily powering off the main server, which will likely result in service interruptions and consequent inconvenience/diminished reliability from a user perspective.
    2. Higher security risks: Having a single point of failure also increases the chances of security breaches or disruptions from cybersecurity threats such as _DDOS attacks_ (https://www.gemini.com/cryptopedia/glossary#distributed-denial-of-service-d-do-s-attack)since there is only one target to compromise. Furthermore, since there is only one central repository for user data, centralized networks will always involve inherent privacy risks. For example, if the main server is corrupted or taken offline, its data may be permanently lost.
    3. Limited scalability: Centralized networks can be hard to _scale_ (https://www.gemini.com/cryptopedia/glossary#scalability) past a certain point since the only way to do so is to add more storage, bandwidth, or processing power to the central server. Furthermore, if the network experiences traffic spikes beyond what the network was designed to handle, information bottlenecks may occur, with users further removed from the central server experiencing increased latency.
## What Is a Decentralized Network?
    1. By contrast, a decentralized network distributes information-processing workloads across multiple devices instead of a single central server. Each of these separate devices serves as a mini central unit that interacts independently with other nodes. As a result, even if one of the master nodes crashes or is compromised, the other servers can continue providing data access to users. Thus, the overall network will continue to operate with limited or zero disruption. 
    2. Decentralized networks are made possible by recent technological advancements that have equipped computers and other devices with a significant amount of processing power and can be synced up and leveraged for distributed processing. However, while decentralized networks are substantially different from centralized networks, it’s important to note that decentralized networks do not distribute data storage and processing evenly across the entire network and still rely on main servers, albeit more than one per network. 
### Advantages
    1. Increased flexibility/scalability: Since decentralized networks do not have a single point of failure, they can continue to operate even if a master node is compromised or shut down. Furthermore, decentralized networks are easy to scale since you can add more devices to the network to increase its computing power, and network maintenance typically does not necessitate a full network shutdown. 
    2. Faster performance: User requests are often completed faster when using a decentralized network because network administrators can create master nodes in regions where user activity is high instead of routing connections over vast expanses to a single centralized server.
    3. Enhanced privacy: Decentralized networks enable greater user privacy since information saved on the network is disseminated across multiple points instead of passing through a single point. This makes data flow more difficult to track across a network and eliminates the risks of having a single target malicious actors can go after.
### Disadvantages
    1. High maintenance costs: Decentralized networks are more fault-tolerant than centralized networks. This makes maintaining these networks typically more costly and labor-intensive. Since a decentralized network relies on multiple devices to underpin the system, this places a commensurate burden on an organization’s IT resources. As a result, decentralized systems are often not suitable for organizations requiring only a small system since the cost/benefit ratio isn’t favorable under these circumstances.
    2. Coordination issues: Since master nodes within a decentralized network act independently and may not communicate, larger organizations may run into coordination issues and have difficulty directing and achieving collective tasks. While this is a deliberate feature of decentralized networks, not all business models and organizational structures will necessarily benefit from using a decentralized network. 


