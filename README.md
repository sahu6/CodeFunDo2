
USING BLOCKCHAIN TO MAKE THE VOTING SYSTEM SECURE AND ELECTRONIC
Why Blockchain?
* Blockchain technology characterised by transparency, mutability and accountability, would be able to ensure more security and authenticity during voting procedure.
* Moreover, Blockchain is immune to alteration of data, which is a required feature in a voting system. Once stored, data can't be altered without altering all subsequent blocks, which requires the consensus of a network majority, making blockchains by design secure, with a very high Byzantine fault tolerance. This aids in ruling out bias and making the process more secure and faster to get results.

OUR SOLUTION

The voting process can be greatly enhanced by using a private blockchain, which will increase security due to the use of peer-to-peer network, and clubbing Azure Blockchain with Multichain.Multichain also supports asset management, which is unique in that one can define an asset and issue Units of asset in the network ("Vote" can be assigned as an asset). Each registered voter will be assigned exactly one vote during the registration process.
This system, alongside blockchain, needs some additional components to ensure voter anonymity and maintenance of the voting data confidentially.For this, an Authentication organisation(like the Election Commission) and a TTP(Trusted Third Party) is needed.

TTP
TTP will act as a bridge b/w EC and the voter to authenticate the voter while maintaining voter anonymity.
The TTP should be a private organisaton that helps in validating the voters during voting. It should ensure that the voter information is kept anonymous to the Authentication Organisation to prevent potential manipulation of votes.
Now, once TTP authorizes voters to vote, the voter can choose whom he wants to vote for within his constituency. This will solve the problem of voters who are registered to vote for in a different area and are living in a different area, as now it would be his unique identity that will allow him to vote, rather than his physical presence at a voting booth. Also, this will solve the problem for Non-Residential citizens of a country as they can also vote, despite being far from their native place.

AUTHENTICATION ORGANISATION
The Authentication Organisation should be the entity that holds voter information.
During electronic voting, the organisation determines voter validity. At the same time, it maintains confidentiality of the voter information.
Furthermore, the Election Commission should provide a user interface to maintain a record of all the valid voters for an election in a constituency. On this interface, each user should be validated and registered using a Unique Identification Number assigned by the EC. This will nullify any chance of the voter registering multiple times with different places or voting multiple times. 
In the registration process, the voter receives a unique reference number to be used during voting. Also, an internally hashed secret message and reference number is generated and stored in the Election Commission database, to be used for cross-referencing during the voting process. Now the unique reference number should not be revealed to ensure the integrity of the voter and remove any chances of vote modifications. 


In the private blockchain we have deployed for our voting process, each vote will be the conceptual equivalent of an asset in the blockchain as the transaction happens. By restricting the Blockchain asset to a process maximum of one transaction between parties, restricting both the options of either multiple votes sent to the same candidate or voting for multiple contenders.
For every candidate, a public address generated by the Election Commission, is stored against the candidate. Then, during voting, this address will be made visible to the voters to vote for candidates.
Finally, during voting, the voter has to get their biometrics verified and then submit the same secret message and reference number that has been generated previously, to the TTP. TTP sends the message hash to the EC to get verification for voter as valid and upon verification, voter will be taken to the voting page and shown a list of candidates according to his constituency. During this process, TTP generates a public key for the voter using the block-chain network and stores this information against the secret message hash and voter reference number. Also, by restricting number of transactions between two parties to one, any attempts to vote multiple times can be invalidated by multi-chain.


Since it’s an Electronic Voting System, reports can be generated in real time. Therefore, after the voting, detailed reports about a candidate's results, party-wise results, constituency results, etc. can be easily prepared by using any AI tool by combining data from multi-chain and data stored in EC records.
