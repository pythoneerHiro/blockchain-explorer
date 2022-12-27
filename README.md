# Blockchain Explorer&Analytics

Query, extract, and visualize vast amounts of data on blockchains

## Idea and Inspiration

In public blockchains such as Bitcoin,Ethereum, all the information is inherently public. All you need is to look for
it. So far, answering questions such as how many users does a project has, or what is the daily volume of a DEX, would
most likely require writing a specialized script. Running the script would involve iterating over blocks, parsing the
information, properly sorting it, and extracting the data.
This can be both time-consuming as well as extremely specialized. Scripts like that would likely be able to extract
information about one specific project but would require extensive modifications to generalize for anything else.
Besides, running on all blocks is a long process in itself, that requires either a full node or many individual queries
to an external service.

I am working on a tool that greatly simplifies the process.
It is a web-based platform for querying Ethereum data by using simple SQL queries, from pre-populated databases.
Instead of writing a specialized script, one can simply query the database to extract almost any information that
resides on the blockchain.

### UseCase 1: query blockchain data at ease

### UseCase 2: build dashboards to visualize the queried data

### UseCase 3: get realtime blockchain data at no additional cost of running a node.

## HLD

<details open>

<summary> Context Diagram </summary>

![context-diagram](https://user-images.githubusercontent.com/109627424/209623701-03639d32-5e97-41aa-be86-9a7adc707382.png)

</details>

<details open>
    
<summary> Container Diagram </summary>

![pyor_container](https://user-images.githubusercontent.com/109627424/209623875-9f4c1f43-b997-41b7-8151-01c85287ab87.png)

</details>

<details open>
    
<summary> Component Diagram </summary>

![pyor_api_component-Component_Diagram_for_Pyor_API_Backend](https://user-images.githubusercontent.com/109627424/209624135-767a78ff-da64-476a-a0d0-cbb1e65791bd.png)

</details>

<details open>
    
<summary> Component Diagram </summary>

![query_bitcoin_data](https://user-images.githubusercontent.com/109627424/209624162-4eafb802-f672-442a-bf77-8e92204ef733.png)

</details>
