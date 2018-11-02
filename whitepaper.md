# HydraNet: MeshNet Solutions

Release Version V1.0 Written By Zapotec0

Release Version V1.1 Written By Kai Haas

Current Release V1.1 June 6th, 2018


# Abstract
Over the years, The internet has become an integral part of modern society. In the early days, the internet was just a handful of disorganized BBS systems connecting through telephone landlines. After TCP/IP protocols were invented, the internet “bubble” exploded, far surpassing the capacity of landlines within a matter of years. Soon cable companies, seeing the opportunity of the internet, took advantage of this bandwidth vacuum, and took control of the market quickly and swiftly, dominating the market and establishing virtual monopolies. High cost of entry and other legal and financial barriers prevented innovation and destroyed almost all competition and innovation in the ISP market. The solution, is a lot simpler than many might think. Mesh networks, or an interconnecting networks of individuals, have been around for quite a while, however the mesh network field has mostly been dominated by hobbyists and network enthusiasts. Despite the limited current audience, the technology has marketable applications and almost unlimited consumer use cases.


# Project Goal
The end goal of the Hydranet Mesh Networking Initiative is to provide a clear and adaptable framework for an international mesh networking system that will attempt to replace the current centralized internet, with economic incentives and ease of use, previously only found in traditional Internet service models. We will provide hardware and infrastructure to the consumer, and implement services and technologies into the existing cjdns networking protocol, and expand the currently limited community meshes, into a worldwide network of consumers and providers, giving the users of the network choice, speed, and reliability not seen before in traditional providers.


                                                                                           
----------------------------------------------------------------------------------------------------------------------------
# Introduction

The many facets and intricacies of mesh networks are vast, and far reaching, and the benefits are undeniable. The reliability, speed, and freedom of choice provided by a mesh networking system is on a much higher level than any other data distribution network prior. The system consists of a nodal network. If you are not familiar with the concept of nodal networks, they consist of multiple nodes(points on a network), having connections with multiple other nodes, and so on. This provides a large level of redundancy, partly because if one node goes down, you have a multiple other nodes to handle the signal. That is partly where we draw our name from, because just like the mythical hydra, if you cut off one head, three more grow back. 

The nodes consist of both mobile devices with built in radios, such as smartphones, wired and wireless infrastructure, and independently owned routers connected to high gain variable direction antennas. The wired and wireless infrastructure, both providing long distance links and providing a backbone for the rest of the network. Secondly the user owned routers and antennas provide the majority of medium range connectivity, and provide businesses, homes, and individuals connectivity to the greater network outside of the users LAN. Lastly, the use of smartphones. The network would utilize the radios inside of the majority of smartphones to connect to the network, and the mobile devices would form a short range mini network, routing data throughout to provide the fastest route to the final destination, whether that be destination a phone, local web server, or a service being hosted 200 miles away.

Users or companies running nodes have the option for incentivisation for their bandwidth. You can either choose to offer your bandwidth, and subsequently a path through your node, for a price, or free of charge. This provides incentives from both users and companies to innovate and increase quality of access, which in turn increases not just network efficiency, but also workplace and personal efficiency. The model for the incentivisation program is very simple, and economically allows for a healthy free market.

Users can run their traffic through others nodes to find the fastest and most efficient path to their final destination. The nodes that this data is being routed through are compensated by the recipient and the host of the data proportionally using an automated payment system using cryptocurrencies. 

Both the host and the recipient can choose priorities for selecting a data path. They can select nodes based on a few factors, speed, reliability, cost, and latency. The recipient’s preference settings will be used for the initial request of data, and the host’s preference settings will be used for the data to be transferred back to the recipient. The cost of the bandwidth shall be split proportionally between the host and the recipient.

Alternatively nodes have the option to provide bandwidth free of charge, of course due to the open and free market, consumer demand and the ability for these nodes to keep up with said consumer demand will determine the amount and availability of these free of charge nodes. 

Considering every user acts as a singular node on the network, this turns the consumer cost of use extremely small, even if the actual price of bandwidth is higher than the overall cost to the consumer. This is because of the ability to monetize the bandwidth that an individual's node has access to, which by extension keeps profits high, and costs low.

The network runs off of an adapted version of the cjdns protocol, specifically made to run a consumer friendly GUI which will allow for widespread use of the technology without need for prior technical knowledge.

                                                                                       
                                                                                 
----------------------------------------------------------------------------------------------------------------------------
# History

The history of the current technology now known as mesh networks is very short. There were a few low level experiments using packet radios in Hawaii in the late 90’s but at the time experiments in alternative wireless data distribution systems were very uncommon. In the mid 2000’s however, this changed.

Some early projects included guifi.net in Catalonia,[1] which was intended to provide broadband to underserviced areas of rural Catalonia in spain, and has garnered over 34K+ nodes. Another more notable experiment was the famous MIT Roofnet Meshnet.[2] The MIT roofnet was an 802.11b wireless mesh networking experiment conducted by the Massachusetts Institute of Technologies Computer Science and Artificial Intelligence Laboratory.  In the experiment they operated around forty nodes, with each node consisting of a computer running custom software, and a roof mounted 802.11b antenna connecting it to the rest of the network. These roof mounted antennas, which gave the network its roof themed name, proved to be effective stationary mesh networking nodes, and considering the low level technology of 802.11b, and the relatively more advanced technology in cellular phones and routers today, the technology would be even more effective than this early experiment.


The most recent and prevailing project has been the protocol cjdns[3] developed by Caleb James Delisle.The cjdns protocol is a IPv6 networking protocol that has been ported to a variety of hardware and software architectures. Cjdns protocol has proven to be an effective and capable protocol for large scale mesh networking. The Hyperboria network runs entirely cjdns, and has long succeeded as a powerful darknet. 

The origins of the current alternative internet movement can be linked back to the subreddit r/darknetplan.[4] The Hyperboria network can be linked back to the r/darknetplan subreddit, and the original volunteer developers of Hydranet can be linked back to the subreddit.

The community as a whole is still relatively active, and most of the ongoing projects organize and communicate offsite. The main hurdle preventing these ambitious projects from reaching mainstream adoption however was lack of commercial viability. These projects were never intended to make money, and the lack of any revenue streams caused these projects to stay in a niche, slowly growing network of enthusiasts. 

During the period of time before and after the United States Federal Communications Commission's ruling on Net Neutrality, the mesh networking community received a large surge of attention and new members of the community. The fear of a monopolized and censored internet brought many to a very real and important realization; the only way to bring freedom to the internet, is to cast aside the old system, and innovate, for the future.
    
The history of the Hydranet Mesh Net Initiative is an interesting and colorful one. We started as a collective ideal, fueled by the motivation of protecting the internet from the monopolies of cable providers, and the potential violation of net neutrality principles by those providers, if the repeal were to pass. On the subreddit r/darknetmesh people were talking. They were talking about an alternative internet, faster, more efficient, and more reliable than the last, and they were talking with more passion and interest than ever before. 

One fateful post, linking to a Discord server dedicated to the organization of the influx of new members, which would eventually become HydraNet, garnered a lot of attention in the community. The most outspoken developers and contributors, helped shape the direction and goals of this organization drastically. The active and intellectual conversation lead to a rapid advancement of ideas, technology, and the overall knowledge and technical ability of the collective. 

However, since all developers and contributors were volunteers, and thus worked on their own time, after a month or two, development had gone quite far, and the idea was solidified and technical problems were solved, and because of lack of funding, we did not have the active resources necessary for dedicated software development. 


----------------------------------------------------------------------------------------------------------------------------
# Infrastructure

The backbone of every network is the infrastructure connecting said network. Traditionally the internet has a very failure prone and rigid infrastructure, in the form of direct connection to an internet service provider, which then connects you to your desired destination. This is a very inefficient system, because there is very limited redundancy and backup.

The main appeal of a mesh networking system is the failure tolerant and self correcting nature of most networks. If one node goes down, there are three more to take its place. It is almost impossible to lose connectivity, and this also increases the amount of bandwidth and information that can be sent through the system at once.

Another of the many features of mesh networks is the increased flexibility and room for improvement and innovation. With traditional networks if you want to transfer to a new protocol or use new hardware with higher capabilities, you would have to remove all the old infrastructure and hardware, and then replace it. This is expensive and inefficient; but with mesh networks all the network hardware is interconnecting and self reliant, therefore replacing one piece of infrastructure will not cause downtime for any other hardware. 

Along with the self reliance of every node, infrastructure is not limited to high powered hardware, as a large part of the network has the potential to be mobile phone radios, while dedicated antenna can mostly be utilized by home and office applications, as well as dedicated commercial infrastructure.

The flexibility of both the market and the network as a whole provides an opportunity for any outcome, depending on market demand. It could be almost completely dominated by mobile nodes, or long range communication could very well be almost entirely supplied by private nodes, it entirely depends on the demand of the market, and the ability to supply, and from which sources are available. This flexibility allows for a sustainable market that can adapt to both consumer and private sector needs.

                                                                            
----------------------------------------------------------------------------------------------------------------------------
# Commercialization
Any emerging technology or field most often will need a revenue stream to be able to burst into the mainstream. Internet Service Providers charged for internet service, internet media companies charged for access to services or content. Mesh networks are traditionally peer-to-peer free networks, which is one of the main reasons it hasn’t entered the mainstream. There wasn’t any reason for companies to invest in a new technology if it couldn’t make money. This is where that all changes
    
The main business model of the HydraNet mesh network is a bandwidth based monetization model. When setting up your node you can decide on a fixed, or variable, per gigabyte price. This price is only applied when your node is the only other node in between the two start and destination nodes. When there are multiple nodes in between the start and destination nodes, an algorithm averages the price of each of the nodes preferred rate, while also taking into account the amount of nodes the data is being transferred through. This calculated price is then split between the start and destination node, and the revenue is split between the intermediaries.

Another source of revenue, is the sale of, and maintenance of hardware and software designed to connect to the HydraNet mesh network. This can range anywhere from producing custom software and clients to interface with the network, to developing custom hardware or consumer ready devices. 

The development team will be funded and upheld by the revenue generated by premium first party routers, antennas, kits, and premium/enterprise clients. The core software, firmware, and hardware will remain open source, allowing for third party development and innovation, however premium first party accessories, hardware, and software will be closed source proprietary software, with intention for use by enthusiasts, enterprise, and large scale infrastructural use cases, however can be purchased by casual consumers.



----------------------------------------------------------------------------------------------------------------------------
# Hardware
There is a few classifications of the standard hardware configurations. Firstly there is long distance infrastructure. Secondly we have local area nodes. Lastly we have mobile devices. These hardware configurations fill a variety of roles, each with their own specific desired use cases. These are the main configurations, however because of the flexibility of the open source options the configurations that could possibly be in use is almost infinite.

The first of the main hardware configurations is long distance infrastructure. This mostly consists of long distance, high bandwidth, communications devices. These can range from large antennas for interstate communications, to undersea cables, and even low orbit satellites depending on the budgeting of the provider. These are mostly used for intercity, interstate, and even international connection, that connects one regional meshes with other regional meshes.

The second of the main hardware configurations is local area nodes. These consist of smaller wireless antennas, and personal wireless routers. These connect local nodes with others in the surrounding area, and possibly in neighboring cities if the connection is ideal. These are used for personal and localized enterprise use, and mostly consists of a high gain antenna connected to a router running an OpenWRT[5] version of CJDNS[6] running HydraNet software.

The third of the main hardware configurations is the mobile device classification. This consists of extremely short range signals that connect to other mobile devices, as well as the local area nodes, and sometimes long distance nodes. This uses a mobile version of a HydraNet client, and utilizes the radios found inside of mobile devices, to connect to the desired nodes around them. This can be used for short range communication, such as phone calls and text messaging, as well as multimedia applications typically found in use in mobile devices.


All of these hardware configurations combine to create an extensive and adaptable network that can take many shapes, sizes, and configurations.


----------------------------------------------------------------------------------------------------------------------------
# Software
The software of choice for mesh networking enthusiasts has varied throughout the years. Some of these choices include Babel,[7] B.A.T.M.A.N,[8] and of course the current prevailing king of mesh nets, CJDNS. 

The HydraNet interface will be a streamlined version of the CJDNS protocol, adapted for usability, bandwidth management and monetization, and other notable features. The interface allows for ease of use, compatibility, and monetization never before seen in large scale mesh networking projects.

One of the main software interfaces being implemented is a dedicated node client. These clients would install on OpenWRT compatible routers, and could be adapted to other enterprise hardware, and also are available for standalone antenna connections to personal computers, using a software package for your desired operating systems.

The second software interface is designed for mobile platforms. It is designed for the use of mobile radios and touchscreen displays. The protocols and features are virtually identical to the same interface from the previous use cases, simply adapted for use for mobile devices.

All of these clients and interfaces connect together and form a powerful network. The streamlined programs allow for maximum interconnectability and compatibility. The open source nature of the basic interface and software, the ability for improvements to the clients and software is endless, and said improvements therefore improve the network as a whole.

There is possibility for multiple channels and providers for client software and interfaces. A few of these possibilities include both first party premium and open source, and third party premium and open source software. This allows for the possibility of nonprofit, and commercial providers of software.


----------------------------------------------------------------------------------------------------------------------------
# Conclusion
With the proper funding, and public adoption, mesh networking, and more specifically HydraNet, could prove to be an effective and reliable alternative to traditional networking solutions. 

The simple open ended nature of the network allows for endless possibilities of hardware and software end user configurations. The commercialization options for both end users and commercial operations are vast and adaptable to consumer and network needs.

The decentralized nature allows for privacy and freedom shown by few networks in the past. Previous privacy issues shown by providers and governments will be much more avoidable with this network.


In conclusion, HydraNet has the potential to be a revolutionary network that could change the way we communicate.


----------------------------------------------------------------------------------------------------------------------------
# References
[1]“Guifi.net Commons Telecommunications Network.” Guifi.net, 2004, www.guifi.net/en

[2]Bicket, John, et al. “Architecture and Evaluation of the MIT Roofnet Mesh Network.”MIT.edu, https://pdos.csail.mit.edu/~rtm/roofnet-b.pdf

[3]Delisle, Caleb J. “Cjdns.” GitHub, 31 Jan. 2018, www.github.com/cjdelisle/cjdns

[4]Anon. “r/Darknetplan.” Reddit, www.reddit.com/r/darknetplan/

[5]Anon. “OpenWRT.” OpenWRT, 2 Feb. 2017, www.openwrt.org/

[6]DeLisle, Caleb James. “SeattleMeshnet/Meshbox.” GitHub, 25 Feb. 2016, www.github.com/seattlemeshnet/meshbox#cjdns-on-openwrt

[7]Chroboczek, Juliusz. “Babel.” Babel, 1 Jan. 2011, www.irif.fr/~jch/software/babel/

[8]Freifunk. “B.A.T.M.A.N.” Open-Mesh, 19 Mar. 2018, www.open-mesh.org/


                                                                                            
----------------------------------------------------------------------------------------------------------------------------
Last Update 6/05/18
