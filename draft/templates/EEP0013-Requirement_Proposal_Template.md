    EEP: EEP0013
    Title: Requirements Proposal Templates
    Author: Joaquin Prado
    Type: Process
    Status: Draft
    Created: 2017-12-11
    Requires (*optional): <EEP with the related Use Case Number>
    Replaces (*optional): N/A
    Branch: eep-0004 (Working Group Process)

# Use Case Domains
Based on the Use Case listed in the head of this document: ```EEP-xxx-title.md```, subject matter experts should provide the following analysis:

Domain        | Description
-------------:| -----------------------------------------------------------------------------------
Legal         | What do you need to do in order not to go to jail or be sued?
Regulatory    | What do you need to do in order not to loose your operating license.
Finance       | If you can't make it for itself, it isn't going to work.
Accounting    | Make it easy to account for your activities or face high costs of doing so or worse lose your license.
Audit         | If it can't be audited and reported, it can't be approved by regulators.
Tax           | Death and taxes, so make it's easy to pay them or they will be the death of you.
Operations    | Make sure you can operate the solution in cost efficient manner.
Business      | Get to know you business functional and non-functional requirements, they drive your revenues.
Technology    | Makes sure your requirements are technically implementable.
Risk          | Consider all of the domains from what-can-fail point of view, and propose mitigation requirements.

# Competing Factors

Factors/Levels       | EF | Description                                                           | 0  | 1  | 2  | 3  | 4  | 5  | 
--------------------:|----|:---------------------------------------------------------------------|:---|:---|:---|:---|:---|:---|
Privacy              | 5   | Does anyone know who are you and what you do?                        |No  |    |    |    |    |Yes |
Confidentiality      | 0   | How easy it is to share some data with a sub-set of participants and make sure others can't access that data.                                                                    |No    |    |    |    |    |  Yes  | 
Performance          |1    | How quickly can a transaction be settled e.g. 10 mins minimum for Bitcoin, 12 seconds minimum for Ethereum. |  |10mins|tbc |tbc| tbc| 1sec|
Scaling              1     | How many transactions can be settled within a specific time frame e.g. 1 second.| |15tx/s |tbc|tbc|tbc |100K tx/s|
Censorship-resistance|5    | Can a central authority prevent miners confirming transactions, or unilaterally increase money supply? | | | | | | |
Trust                |5   | How likely is it that someone can subvert 51% of the network i.e. number and independence of nodes matters. | | | | | | |
Compliance           |1  | This is a tricky one, but largely can the system support existing regulations. Needs more work. | | | | | | |
Finality             |3 | Can transactions be reversed, and if so how long for and what are the chances of doing so. | | | | | | |

