
[URL to this page](http://bit.ly/2yQxJpo) http://bit.ly/2yQxJpo 

# 2017-10-23-Blockchain-at-Galvanize 
Learn how to start writing Blockchain applications

[EventBrite](https://www.eventbrite.com/e/learn-how-to-develop-blockchain-apps-tickets-38129072081)

# Housekeeping info:
[Eventbrite Invitation](https://www.eventbrite.com/e/learn-how-to-build-fintech-applications-that-use-watson-ai-tickets-37213362168)

### Wifi at Galavanize SSID/pass = g|Events / machinelearning
Your instructor: Lennart alf@us.ibm.com

## Assumption: you already know enough of Blockchain to want to learn to write Blockchain apps. 
## Intro to Blockchain for newbies http://bit.ly/2yIuhJs

# Agenda
~~~
6:00  Sign-in, mingle, food, welcome. Intro of Tom Eck, IBM CTO Industry Platforms
6:20: Introduction to IBM Blockchain and Hyperledger: 
6:30: Lennart: Introduction of the labs (Developer Journey). 
6:40: Coding starts.
      Lab 1: Bringing up the Hyperledger Fabric 
      Lab 2: Running your first application
      Lab 3: 
8:00: Coding ends.
      Where do we go from here?  
      Lab 2: 
      Lab 3:
8:30: Event ends   
~~~ 

# Let's get started: Blockchain and Hyperledger

(http://hyperledger-fabric.readthedocs.io/en/latest/samples.html)

Hyperledger, an open source collaborative effort to advance cross-industry blockchain technologies, 
is hosted by The Linux Foundation®. 

IBM provides blockchain solutions and services leveraging Hyperledger technologies, 
including Hyperledger Fabric and Hyperledger Composer.

## [Hyperledger Composer on GitHub](https://github.com/hyperledger/composer)
Hyperledger Composer is an application development framework which simplifies and expedites the creation of Hyperledger fabric blockchain applications.

## [Hyperledger Fabric on Github](https://github.com/hyperledger/fabric)

* Hyperledger Fabric is a platform for distributed ledger solutions, underpinned by 
a modular architecture delivering high degrees of confidentiality, resiliency, 
flexibility and scalability. It is designed to support pluggable implementations 
of different components, and accommodate the complexity and intricacies that exist 
across the economic ecosystem.

## [The .BNA file](https://hyperledger.github.io/composer/reference/commands.html)
A Business Network Archive (BNA) file is exported by the Hyperledger Composer with the extension of .bna, and contains the definitions all the definitions for a Business Network. It is deployed in a Hyper Ledger Fabric. 
 is an application development framework which simplifies and 
expedites the creation of Hyperledger fabric blockchain applications.

<hr size="50">

# Lab 1: Let's bring up the Hyperledger Fabric!
   
## Step 1
If necessary execute the following three commands to remove Docker instances.
   * docker kill $(docker ps -q)
   * docker rm $(docker ps -aq)
   * docker rmi $(docker images dev-* -q) 
## Step 2   
   * Go to the following URL: http://hyperledger-fabric.readthedocs.io/en/latest/samples.html
   
   Execute the following commands:
   
   * git clone https://github.com/hyperledger/fabric-samples.git
   * curl -sSL https://goo.gl/Q3YRTi | bash 
    Go to the following URL: http://hyperledger-fabric.readthedocs.io/en/latest/build_network.html
   * cd first-network
## Step 3   
   Bring up the Hyperledger Fabric: 
   
   * ./byfn.sh -m generate
   * ./byfn.sh -m up. //See full output from command on this link http://bit.ly/2yyTeIj
   
   * After checking the output, remember to run ./byfn.sh -m down.

# Lab 2: Let's run our first app app in Hyperledger Fabric 
Source: http://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html

## Step 1 Remove not needed artifacts
    * docker rm -f $(docker ps -aq)
    * delete chaincode image: docker rmi dev-peer0.org1.example.com-fabcar-1.0
## Step 2 Navigate to a directory where you want the samples downloaded to issue these commands:
    * git clone https://github.com/hyperledger/fabric-samples.git
    * cd fabric-samples/fabcar
    * See what's inside the directory: ls
    * You should see the following: chaincode , invoke.js , network , package.json , query.js , startFabric.sh
    * Start the fabric: ./startFabric.sh
    * Install the SDK Node modules: npm install
    * cd fabcar
    * node query.js
    ~~~
   Arnes-MBP:fabcar arnelennartfrantzell$ node query.js
   Create a client and set the wallet location
   Set wallet path, and associate user  PeerAdmin  with application
   Check user is enrolled, and set a query URL in the network
   Make query
   Assigning transaction_id:  9367267e0e9c66cba821eb79500ffee6f004ced6f53bc01ddf280b00e2a8cb10
   returned from query
   Query result count =  1
Response is  [{"Key":"CAR0", "Record":{"colour":"blue","make":"Toyota","model":"Prius","owner":"Tomoko"}},{"Key":"CAR1",    "Record":{"colour":"red","make":"Ford","model":"Mustang","owner":"Brad"}},{"Key":"CAR2", "Record":{"colour":"green","make":"Hyundai","model":"Tucson","owner":"Jin Soo"}},{"Key":"CAR3", "Record":{"colour":"yellow","make":"Volkswagen","model":"Passat","owner":"Max"}},{"Key":"CAR4", "Record":{"colour":"black","make":"Tesla","model":"S","owner":"Adriana"}},{"Key":"CAR5", "Record":{"colour":"purple","make":"Peugeot","model":"205","owner":"Michel"}},{"Key":"CAR6", "Record":{"colour":"white","make":"Chery","model":"S22L","owner":"Aarav"}},{"Key":"CAR7", "Record":{"colour":"violet","make":"Fiat","model":"Punto","owner":"Pari"}},{"Key":"CAR8", "Record":{"colour":"indigo","make":"Tata","model":"Nano","owner":"Valeria"}},{"Key":"CAR9", "Record":{"colour":"brown","make":"Holden","model":"Barina","owner":"Shotaro"}}]
~~~
    
## Step 3 

# Lab 2: Let's write an app with the Hyperledger Composer!
## [Run Hyperledger Composer in your browser](https://hyperledger.github.io/composer/)
## [Playground Tutorial](https://hyperledger.github.io/composer/tutorials/playground-guide.html)

# Lab 2: Let's install the Hyperledger Fabric!
## [Getting Started](http://hyperledger-fabric.readthedocs.io/en/latest/getting_started.html)
## [Install prerequisites](http://hyperledger-fabric.readthedocs.io/en/latest/getting_started.html#install-prerequisites)
## [Install Binaries and Docker Images](http://hyperledger-fabric.readthedocs.io/en/latest/getting_started.html#install-binaries-and-docker-images)
## [Hyperledger Fabric Samples](http://hyperledger-fabric.readthedocs.io/en/latest/getting_started.html#hyperledger-fabric-samples)
## [Building your first network](http://hyperledger-fabric.readthedocs.io/en/latest/build_network.html)

# [Writing your first application](http://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html)

# Lab 3: https://developer.ibm.com/code/journey/decentralized-energy-hyperledger-composer/

# Where do we go from here?

* https://developer.ibm.com/code/journey/build-your-first-blockchain-application/
* https://developer.ibm.com/code/journey/create-and-execute-blockchain-smart-contracts/
* https://developer.ibm.com/code/journey/implement-fda-food-supplier-verification-program-on-hyperledger-composer/
* https://developer.ibm.com/code/journey/build-a-blockchain-network/
* https://developer.ibm.com/code/journey/decentralized-energy-hyperledger-composer/
* https://developer.ibm.com/code/journey/run-blockchain-technology-on-a-linux-mainframe/
* https://developer.ibm.com/code/journey/create-a-to-do-list-app-using-blockchain/
* https://developer.ibm.com/code/journey/deploy-an-asset-transfer-app-using-blockchain/



# Notes

* curl -sSL https://hyperledger.github.io/composer/install-hlfv1.sh | bash
* composer network deploy -a basic-sample-2.bna -p hlfv1 -i PeerAdmin -s randomString -A admin -S
* composer network ping -n basic-sample-2 -p hlfv1 -i admin -s adminpw
* https://developer.ibm.com/tv/hyperledger-composer-build-execute-smart-contract/ 

