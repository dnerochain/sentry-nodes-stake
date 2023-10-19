## Delegated Nodes Entries Form Template

### Note:
Fill out the next empty Block with the the follow entries
 
1-id: Enter a Number following the last Entry Number

2-name: The name of your Sentry Node ex: Name Stake Pool or any name that represent your Delegate Service

3-address: Your Sentry Node Address

4- % fee: Your % percentage Fee you want ot charge to your delegators ex: 0%, 1%, 2%, 3%, 4% ...etc

5-node-summary: 0x--Get-Your-sentry-node-summary-by-typing: <dnerocli query sentry> in the terminal. 
Your node-summary should start with your Sentry node address

6: split_basis_point: Your Fee % percentage in numeric ex: 2% - Your split_basis_point = 200

-------------------------------------------------------------------------------------------------------
### Sample to Copy and Fill Out
  {
    "id": Enter a Number following the last Entry Number,
    "name": "Your-Sentry-Node-Name",
    "address": "Percentage % fee - 0x-Your-sentry-node-address",
    "node_summary": "0x--Get-Your-sentry-node-summary-by-typing: dnerocli query sentry in the terminal",
    "split_basis_point":  Your Fee % percentage in numeric ex: 2% = 200 or 0% = 0
  },
--------------------------------------------------------------------------------------------------------
  {
    "id": 6,
    "name": "Muroko-Dev Pool",
    "address": "0% fee - 0x-Your-sentry-node-address",
    "node_summary": "0x-----------Get-Your-sentry-node-summary-by-typing: dnerocli query sentry in the terminal",
    "split_basis_point": 0
  },
  ###
  {
    "id": Enter a Number following the last Entry Number,
    "name": "Your-Sentry-Node-Name",
    "address": "Percentage % fee - 0x-Your-sentry-node-address",
    "node_summary": "0x--Get-Your-sentry-node-summary-by-typing: dnerocli query sentry in the terminal",
    "split_basis_point":  Your Fee % percentage in numeric ex: 2% = 200 or 0% = 0
  },
  ###
