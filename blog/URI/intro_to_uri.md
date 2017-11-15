# Open Science Organization - Introduction to the Unique Research Identity

## Open Science Organization (OSO)

The Open Science Organization (OSO) is an open source initiative focused on building the future ecosystem that thought leaders, researchers, and academics utilize to collaborate, promote, and share ideas. OSO will be a flexible non-profit [Decentralized Autonomous Organization (DAO)](https://en.wikipedia.org/wiki/Decentralized_autonomous_organization) jointly owned by scientific researchers and public to manage an open, democratic, and efficient end-to-end scientific ecosystem.  OSO is dedicated to the [Open Science](https://en.wikipedia.org/wiki/Open_science) mantra and driven to expand upon it by integrating the open science principles with the decentralized and distributed technologies being introduced and popularized by the Web 3.0 framework.

Current frameworks are centralized by domain and reliant on a handful of aggregators to distribute, search, and access information.   Within the current ecosystem there are many points of friction that restrict access to information, mask the peer review process, and cascade into more complex issues such as idea attribution, reliable reproduction of research, and research funding.  These challenges require unique solutions and significant buy in from the research community.

In order to achieve our vision we believe that the technology is important, but user input and experience will lead to greater adoption which will be vital for the health of an ecosystem that has been presented.  Having those that use the product contribute ideas and preferences as part of the design will ensure the research experience meets the researchers needs to contribute to the wider ecosystem.  To help drive this conversation we encourage thoughts and suggestions from the community in what we are calling [OIP's (OSO Idea Proposals)](https://github.com/open-science-org/OIPs/issues), to help start the conversation on our GitHub repository.

## Why URI?
There are many steps required to achieving our vision and the first initiative will be to define, design, and deploy the [Unique Research Identity (URI)](https://github.com/open-science-org/URI).  The URI will be designed so that each entity involved in the research process can be identified and designed to integrate existing systems to help build identity and history (Google Scholar, Research ID, etc.).  This attribution will allow anyone to contribute to the process as well as ensure fairness and transparency.  Currently, we are in the early design and proof of concept phase of building the URI as we develop towards an alpha release.  An initial design of the ecosystem looks like the following:

![OSO Network](https://raw.githubusercontent.com/open-science-org/URI/master/open-science-org-network.png)

As the initial design suggests, our plan is to integrate with other projects that give us much needed tools to identify, govern, store, and reward users.  For the URI we need to provide a transparent method to integrate multiple systems and store this in a distributed fashion so that it is referenceable, regardless of the platform being accessed.  An example of this thought would be to store data on something like the InterPlantary File System (IPFS) and be able to choose the Blockchain of preference.  To start out we will focus on using the Ethereum stack due to the wide array of projects in the ecosystem and the simplicity of integrating with web3 and JavaScript.

To help visualize the layers of the stack from bottom up the following design can be used:

![URI Architecture](https://raw.githubusercontent.com/open-science-org/URI/master/uri-stack.png)

## Identity and Authentication

Since the end goal of any project in the blockchain space should be focused on user adoption we need to ensure that interacting with the platform is as seamless as possible.  To help with this we are looking into the possibilities of integration with projects such as Civic or uPort and biometric based identity.

## Storage

The peer review process requires storage of drafts, revisions, reviews, and data sets used as part of the scientific process.  Each step requires storage and the functionality basics of it need to be reachable via the blockchain.  Possible solutions for this space are [IPFS](https://ipfs.io/), [Ethereum's Swarm](https://github.com/ethersphere/swarm/wiki/roadmap), and for completeness [Sia](https://sia.tech/) or [Storj](https://storj.io/index.html).  The ability to tie a hashed location to one of these distributed storage mechanisms will allow this data to be stored on the blockchain and referenced via the user interface on the OSO network.  This will ensure that the data cannot be restricted nor can it be manipulated via checksum verification.

## Reputation

The reputation score will be based on how each user contributes towards the community, this includes publications, reviews, documentation, data gathering, and various other data points.  All of this will combine into an aggregate reputation level that can be traced via a [Directed Acyclic Graph (DAG)](https://en.wikipedia.org/wiki/Directed_acyclic_graph) of information points along the process.  The level of reputation will eventually assist in creating a score around each of the entities to help determine what is reputable and accepted by the community.

## Aggregation

Integrating disparate sources of information is not something that the current state of blockchain technology is good at handling since it requires the resource to always be available to every verifier on the network.  This is where Oracle's have seen a rise in popularity as a way to bridge this divide and help provide API access to information outside of the blockchain.  In this way we envision projects like [Chainlink](https://link.smartcontract.com/) or [Oracalize](http://www.oraclize.it/) to assist in the initial gathering of information on users joining the OSO network to help tie in past work and information to their URI.


The above list is an initial pass at options to build a trusted ecosystem on the Ethereum stack, feel free to join our conversation at the following locations:

GitHub
Twitter
etc.
