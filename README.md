# Bitreserve_1099_calculator
A calculator to allow customers to calculate their gains and losses on all Bitreserve transactions for US tax purposes.
### The most basic use case of this project:
A user clones this repo and runs it locally using their own personal transaction data that they are able to retreive from the Bitresrve API.
This project is not yet ready for that use. I still need to write the script that takes the JSON from the Bitreserve API and converts 
it into the appropriate data structure for this program.

### Next steps:
Writing a program that will generate transaction objects that function exactly the same way as the transaction objects that a user
can acquire using the Bitreserve API. Once I have enough test data then I can write the script that converts the JSON transaction
objects into 2d lists. The current script operates on 2d lists. 

### Possibilities for this project:
This work could potentially be used to create an internal tool for support to use when requests for 1099 information comes in.
Left to my own devices this would be a Flask app with a simiple HTML interface. And it would live on The Vault or where ever the support tool lives. I'm certainly open to different ways of doing this if we decide that we want this to become and internal tool.

Or, if time permits, I could take time to learn Angular JS since that is what Braga is using. Then this could be turned into a
user facing feature. 
