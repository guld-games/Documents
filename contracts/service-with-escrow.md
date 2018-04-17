# Contract for services

This contract is a contract for services for the benefit of Party A and to be performed by Party B.

The parties agree that all fees for services shall be held by a trusted source and released upon confirmation of services provided.

This contract is specifically intended to hold funds for Party A for a variable period of time by a trusted source known as ESCROW.

Party A, also known by Party A’s cryptographic fingerprint `________________________`, shall deposit funds to be distributed to Party B, also known by Party B’s cryptographic fingerprint `______________________`, upon verification of services performed and completed by Party B.

*(Note: insert code)*

This contract for services is fully funded. Party A is required to fully fund this contract prior to Party B commencing services.

Party A and Party B agree that all transactions shall be in Guld. The value of Guld versus any other currency or unit of value is immaterial to the operation and function of this contract.

Party A shall deposit Guld into trusted ESCROW in the amount of __ Guld.

Party B is not bound to begin services until such time as the amount is fully funded in ESCROW.

*insert code to create escrow services contract and demonstrate that Party A has fully funded and signed the transfer of funds into escrow.*

*(Question: can GuldOS send a message?)*

## SERVICES to be Performed

Party A requests Party B provide ____________________________ services for the benefit of Party A.

Party B represents that Party B is capable and able to perform the services requested in a competent and timely manner based on the specifications and requests of Party A.

Party B represents that services will be provided as follows:

1. Perform Service A.
1. Perform Service B.
1. Perform Service C.

Party B represents that SERVICES shall be completed by *DATE* (UTC time).

## Signatures

Party A signs

Party B signs

## Optional Steps

IF services are to be performed in stages with multiple payouts based on milestone completion, repeat SERVICES section for each milestone: i.e. SERVICES_sub1, SERVICES_sub2, etc.

Export SERVICES to be performed and timeframe into separate file and require separate cryptographic signature by both parties for each SERVICES representation. Later, when date for SERVICES to be completed, if SERVICES are completed and verified by Party A and Party B, RELEASE to Party B. If by date, neither signature is received – do not RELEASE, goto DISPUTE RESOLUTION.

## Progress Reports

Party B shall create progress reports and sign with fingerprint. Party A shall dual sign progress reports upon request unless progress was not completed. ###Use this section for detailed contracts that require multiple stages – for example, if a service contract is divided into 10 stages, and Party B needs to show work on Stage 1, which may have 10 components to completion, Party B may use Progress reports to show work achieved during the stage to achieve the end goal for payout. If Party B completes all 10 components to Stage 1, and signs Stage 1 complete, but Party A refuses to sign to pay, Party B will have evidence in dispute resolution that work was completed and Party A is operating in bad faith.

## Dispute Resolution

IF Party B does not reasonably complete services in a timely or workmanlike manner, Party A may withhold payment until services are completed in a reasonable and workmanlike manner.

IF Party B believes that payment is withheld unreasonably, Party B may enter dispute resolution.

Party B requests Dispute Resolution by signing dispute resolution contract. Party A shall have two weeks from the UTC time of Dispute Resolution filing to respond by signing the Dispute Resolution contract and depositing 20% (_this number may change based – first number that came to my mind_) of the value of the contract into DISPUTE_ESCROW. If Party A does not sign and fund ESCROW, original payment under dispute shall be paid to Party B.

IF Party A signs and funds DISPUTE_ESCROW, Party B shall have 2 weeks to deposit 20% of the contract value into DISPUTE_ESCROW. If Party B does not deposit, Party B forfeits dispute resolution and Party A receives refund.

If Party A and Party B match and fully fund DISPUTE_ESCROW, the value of funds in DISPUTE ESCROW shall be transferred to RAADYX_DISPUTE and a new case shall be created and submitted for dispute resolution. All contracts, signatures, and activity shall be copied into the RAADYX_DISPUTE repository.

The remaining balance of funds in SERVICE_ESCROW shall be transferred to RAADYX_DISPUTED_AMOUNT and RAADYX dispute resolution services shall be the sole signing authority of how and when funds are transferred.
