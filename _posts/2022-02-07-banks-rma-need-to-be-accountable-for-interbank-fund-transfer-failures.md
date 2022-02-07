---
layout: post
title: The curious case of the lost interest income during inter bank fund transfer failures
published: true
author: diwaspuri
color: lightblue
tags: RMA bank interbank fund transfer mpay mbob
---

The recent news about the two telecommunications companies being penalized for poor service is encouraging. Those who fail to deliver on their promises must be held accountable. Similarly, other Bhutanese organizations must also be held accountable for failing to comply with the standards that they promise to its customers. Banks have one of the most pressing requirements for accountability reform. More precisely, the parties facilitating the interbank financial transfers, including remitting, receiving and the central bank.

### How does interbank fund transfer work?

When a person sends money from one bank to another, there are not just two banks involved but also the central bank via which all transactions are routed. The diagram below illustrates the mechanism of transaction.

<div class="mermaid">
sequenceDiagram
	Sender Bank->>RMA BFS: transfer request sent to RMA's BFS for routing
	RMA BFS->>Receiver Bank: transfer amount sent to receiver bank
</div>

For instance, when a BNB customer inserts the details in MPay to transfer funds to a BOB account, the money initially gets debited from his/her account at BNB. After that, RMA's Bhutan Financial Switch (BFS) receives the request to process the transfer to BOB. If the account information given by the customer is valid, the BFS routes the amount to the corresponding BOB account. The success of these steps, more often than not, relies in two things;

- The availability of the RMA's BFS switch that handles the routing of the transaction
- The availability of the receiving bank's core IT systems

Transactions will be halted if any of these companies fails to guarantee that their systems are operationally sound. This means that, using simple combinatorial mathematics, there are six possible ways for the transactions to fail. 

When the fund transfer doesn't go through, the same amount gets parked away into an account without accruing interest as it normally would have, had it been in the savings account. It is only on the following day that the bank officials check for all failed transactions and 'force credit' it to the beneficiary after validating necessary information with the remitting bank.

### Consequences of Fund Transfer Failures

Nobody initiates funds transfers with the expectation that they would be received by the recipient the next day. The consequences of such a transaction failure are rather costly. For example, if a person's transaction of Nu. 500,000 fails, he or she must forfeit Nu. 68.5 that would have accumulated as interest for a day. However, no interest is added to the sum when it is credited the next day. Customers are presently bearing the brunt of the repercussions of bank system failures in the form of lost interest income. This must change.

### Indirect Consequence

BOB has such a significant market penetration in terms of the number of people who utilize their services that the phrase "money transfer" has become synonymous with mBOB. Furthermore, because of the widespread use of the mobile application, mBOB accounts for about 90% of all financial transactions in Bhutan.

When a customer who has an account in another bank comes into the shop wishing to pay using the app that his/her bank provides, it is often revealed to them that owing to frequent failures associated with interbank fund transfers, the shops would not be accepting the payments unless it is from mBOB. It must also be noted that 'intra-bank' fund transfer which happens within the same bank, doesn't require the transactions to go via RMA and are 100% successful every time. It stands to reason that retailers would want to receive payments as soon as possible, which is why they encourage mBOB payments. This promotes payment flows that do not need to go through RMA because they are failsafe.

This phenomenon comes at the detriment of the bank's reputation in the market and fosters monopoly.

### Conclusion

Initiating inter bank fund transfer is a gamble in Bhutan. If either of the 3 systems are not working as they are intended, the transactions fail. To make matters disappointing, none of the three entities involved in the process take accountability for the failure denying customer their right to lost interest. It makes sense that the customers are given interest on their amount the next day when it is credited, if the systems can't be make 100% foolproof.


