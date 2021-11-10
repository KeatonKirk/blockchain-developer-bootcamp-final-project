# blockchain-developer-bootcamp-final-project
WILL BE UPDATING PROJECT IDEA TO REFLECT NEW INVOLVEMENT IN ALGOVERA DAO.

Compensation tool for DAO. Testing SC PUSH!!



Outline:
My Final project will be a crowdfunding application that lets users independently and anonymously raise
funds for registered nonprofit organizations.

The dApp will programmatically ensure that user funds only go to the registered owner of a verified nonprofit, and that funds are automatically returned if the fundraising goal is not met.

Contributors to nonprofit projects will be able to vote to return all donations if funds are not claimed by registered owner of the nonprofit x days after the conclusion of the fundraising campaign.

Application will send all required tax information to non profit owner upon claiming of funds.

Tech Stack:
https://projects.propublica.org/nonprofits/api
Application will use the Pro Publica nonprofits API to get available public data on any registered non profit. Pro Publica API provides all info for registered non profits, including the 990 tax filing. The 990 includes legal owners of each registered non profit, as well as the owner's phone number.

OPTIONAL FEATURE:
Use OCR software (i.e. impira https://www.impira.com/product/technology) to automatically get owner info and phone number from filed 990.

Considerations:
Only the registered owner who appears on the filed 990 can "claim" the funds from a crowdfunding campaign by requiring 2FA via the listed phone number (need 2FA provider).

Similar Projects:
The Giving Block: https://thegivingblock.com/services/accept-crypto-donations/