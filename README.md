# Blockchainproject
This is a small Blockchain project to demonstrate how blockchain can be adopted to a simple rice supplychain.
THEORY

Here we have considered 4 parties of supplychain as 4 nodes in the blockchain.
The transaction between 4 nodes in chain is taken as the data transfer between 4 parties of supplychain.

The four parties are:

1) Supplier/procurement Centre : The supplier collects rice from the farmers as paddy grains and loads to trucks.Harvested paddy is packed into bags and those bags are labeled with specific tags.Digital profiles of the rice bags are created on to the Blockchain and key informationregarding paddy is uploaded during the transaction. The key information couldbe harvest location, date etc. After selling paddy to processing companies or atlocal yields a transaction is initiated between the supplier and the manufacturerand uploaded on to the Blockchain. A new block is added to the chain when they submit this data with a time stamp.

2) Manufacturer/ Processing unit : After receiving paddy, processing enterprise will convert paddy to rice by cleaning, husking, polishing, storing and packing. During the processing, the inserted tags of the paddy may be destroyed but their digital profiles are kept on updated. While sending rice packages to distributors they are labeled with new tags and are configured with their digital profiles on to the Blockchain.

3) Distributor: The Distributor node uploads data regarding the item name, sack code and temperature when they receive at stock rooms and godowns. A new block is added to the chain when they submit this data with a time stamp.

4) Retailer : At retailing node when retailers receive specific rice bags, they nearly obtain and can audit all the information regarding the activities involved in the supply chain of particular rice. Any customer who visits the retailer with a particular software linked with the Blockchain can enter the code onto the customer user interface of the specific rice bag and gain all the information related to supply chain of specific rice. Furthermore, as entire supply chain network is transparent, the possibilities of frauds and scams to happen will be reduced to maximum. 


In this project....

The system developed has 4 Nodes and each node is provided with login cre- 
dentials, each node can log in to their portal by respective key code and password. 
Each node has a dashboard where they can add details and upload documents 
regarding payment, quality tests, contracts, etc. Whenever a node submits the 
data, a block is created at the end of the chain, and at the customer end, they 
can view the product path through which the item reached them. The contracts 
written in solidity defines the ways how the parties involve and their functional- 
ity. The migrate function is used to connect these rules to the application while 
running the application. The front end HTML is connected to this solidity using 
Web3, Web3 act as the bridge between front-end and back-end. Currently we have 
deployed the project in a localhost, network developed in the system using testrpc 
also popularly known as ganeshcli. Initially the project runs, a block is formed 
describing the solidity code hence the shape of the blockchain network, then 2nd 
block is formed when the localhost opens and details like which node opens and 
which parties are logged in etc. For every event that occurs in the front end solid- 
18 
ity functions run the series of functions and ensure it complies with the specified 
program and the event is noted and a new block is formed at the end of the current 
chain. For any change made a new block with the change data, and details like the 
owner of the block are formed at end of the chain with a timestamp. Hence we get 
who changes the data and once the ownership associated with an item is changed 
the previous owner cannot change data regarding the item. 

The README2.md file gives the information on how to run the project , requirements and related technologies used.



