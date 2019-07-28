# Online-Voting WebApp and Digital Identification

This project has:

* A **Blockchain based Voting WebApp** (Online-Voting)
* A **Digital Identification System** to help with **Refugee Crisis and Citizenship**

 
## Online-Voting
Current electronic voting systems are centralized by design and a single supplier controls the code base, database and the system outputs and supplies the monitoring tools at the same time. They lack an open-source, independently verifiable output to gain the confidence required by voters.

We use the decentralised property of Blockchain as a secure transaction database, to log votes and audit vote results.

[Handbook of Digital Currency:
Chapter 22 - Blockchain Electronic Vote](https://www.sciencedirect.com/science/article/pii/B9780128021170000229)

### Properties 

* **Ballot privacy:** No one can know whom the voter voted for.
* **Individual verifiability:** The voter can verify his ballot is counted correctly after he voted.
* **Eligibility:** Only the legal voters can enroll the voting event.
* **Accuracy/Completeness:** Every votes should be counted correctly.
* **Fairness:** Nothing can influence the result of voting.
* **Uniqueness:** Every voter can only vote once. 
* **Robustness:** Anyone cannot influence or modify the final voting result when tallying.

### Implementation
#### Voting Process will have 4 aspects:

* **Registration**

	1. Voter Registration: Voter can register online or they may approach the Election Authority to get themselves registered. Each voter receives a 'Voter ID'.
	2. Candidate Registration: The candidates goes to the Election Authority (EA) and gets his documents and identity verified. The EA registers the candidate into the system and each candidate receives a 'Candidate ID'.
	
* **Voting**
  
	1. Voter logs in and selects his/her choice from a list of candidates on a friendly Web Application.
	2. The Voters choice and their identity will be kept anonymous by the use of [Ring Signatures](https://www.youtube.com/watch?v=zHN_B_H_fCs).

* **Tally**:
		
	1. Vote Counting by reviewing and validating transactions made to each of the candidates.

* **Verification**:
 
	1. Voters can use the Transaction/Voter ID to verify if the signature is published in the right way.
	2. Candidates can check the count of votes in his/her favour through his Candidate ID.


## Digital Identification
Worldwide, a new surge in refugees is occurring. From the southern border of the United States to the Middle East to Myanmar, the number of displaced keeps on growing. More than 50 million people are estimated to have been forcibly displaced from their homes.

### Inspiration
* [Forbes: How Blockchain Can Help With The Refugee Crisis](https://www.forbes.com/sites/rogerhuang/2019/01/27/how-blockchain-can-help-with-the-refugee-crisis/#70dba9406562)
* [World Economic Forum: Blockchain can change refugees lives](https://www.weforum.org/agenda/2018/06/three-ways-blockchain-change-refugees-lives/)
* [Can Blockchain keep Refugees from becoming 'Invisible'?](https://brightthemag.com/can-blockchain-keep-refugees-from-becoming-invisible-technology-innovation-disaster-52981d654385)


### Blockchain solution
The Blockchain will host and transact valued assets and identity proofs through its publicly distributed ledger. Identities verified on the blockchain cannot be faked, and are time-stamped and public.

Refugees could use these documents on Blockchain to prove their identity and that of their families, open bank accounts, sign contracts or apply to university.


#### Team Members:
1. [Aman Toppo](https://github.com/amntoppo)
2. [Saurav Kumar Singh](https://github.com/saurav3199)
3. [Adnan Azmat](https://github.com/adnan-azmat)

Birla Institute of Technology, Mesra
