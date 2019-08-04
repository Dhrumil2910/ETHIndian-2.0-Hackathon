Elevator Pitch:

To secure the organ donor’s medical records using data encryption until his/her demise and then delegate access to concerned authorities using NuCypher’s PRE network and Shamis’s Secret Sharing Scheme.


What it solves:

In 2017, Personal details of over 200,000 Malaysian organ donors and their next of kin have been leaked, with the data available online for over a year. Leaked data includes the donor’s name, identification card number, race, nationality, address, and phone numbers. The data also contains details of each organ donor’s one nominated next of kin, taking the total number of data leak victims to 440,000 (https://today.mims.com/latest-data-breach-of-organ-donors-forces-organisations-to-heighten-security-measures).

This application helps organ donors to safely and anonymously store their medical records using data encryption on a decentralized platform like IPFS until their demise and then delegate access of their data, to their trustee/s as well as to the concerned authorities like Hospitals, which may perform organ transplant after certain verifications.

Scenario:
Let’s say Alice wants to donate her organs after her demise. She collects all the necessary documents like Identity Proofs, Medical check-ups, Official Organ Donation documents etc and encrypts the data using her private key [P(A)], and then encrypted data will be uploaded on IPFS storage. Using NuCypher’s Policy Protocol, Alice will be able to write a policy statement granting access to all the medical data related to organ donation to a Medical Institution. Alice’s Identity will always remain anonymous in the network.
Using Shamir’s Secret Sharing Scheme, Alice will divide her private key [P(A)] into 2 sub-keys [P(A1)] and [P(A2)] and hand it over to her trustees say, Bob and Carel. So that after Alice's death, Bob and Carel together can take in charge of the medical documents and grant access for Alice’s data to a Medical Institution so that all the procedures of organ transplant can be executed on time (before the body starts decomposing). And also Bob and Carel cannot individually access/tamper Alice’s data using sub-keys. So Secret Sharing solves the problem of data tampering after Alice's death.


Challenges:

Understanding and going through the codebase of NuCypher and the demos they supplied was a challenging task but we are proud to be able to have implemented the architecture that allowed us to perform off the chain decryption based on a condition stored on-chain.
