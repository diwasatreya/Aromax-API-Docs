  <div align="center">
      <img src="api-banner.png" alt="Aromax API">
      <h1>Aromax API Docs</h1>
      <p>Documentation of API's provided by Aromax Development</p>
    </div>
    
   <h2><center>Choose an API too see its information:</center></h3>
   <ul>
  <li> <a href="#chatbot-api">Artificial Intelligence Chatbot</a> </li>
  <li> <a href="#fetch-user">Discord User Information</a> </li>
  </ul>
    
   <h3 id="chatbot-api">Artificial Intelligence Chatbot</h4>
<details>
  <summary> Read More!</summary>
  
  ### Example [ Node.js ]
  ```js
const fetch = require("node-fetch").default;
  const mes = "Hello, How are you?"
fetch(`https://aromaxdev.xyz/api/chatbot?message=${mes}`, {
        
    })
        .then(res => res.json())
        .then(data => {
       console.log(data.message)
        })
  ```
  
  ### Using Parameters
  ```
  https://aromaxdev.xyz/api/chatbot?message=<string>&name=<string>&gender=<string>
  ```
  
  | Parameter | Type | Description
  | --- | --- | --- |
  | `name` | `string` | Sets chatbot's name
  | `gender` | `string` | Sets chatbot's gender|
  | `developer_name` | `string` | Sets chatbot's developer name
  | `user` | `string` | Put an ID here|
  | `age` | `string` | Sets chatbot's age
  | `birthday` | `string` | Sets chatbot's birthday|
  | `birthplace` | `string` | Sets chatbot's birthplace
  | `birthyear` | `string` | Sets chatbot's birthyear|
  | `religion` | `string` | Sets chatbot's religion
  | `actor` | `string` | Sets chatbot's favourite actor|
  | `actress` | `string` | Sets chatbot's favourite actress
  | `artist` | `string` | Sets chatbot's favourite artist|
  | `author` | `string` | Sets chatbot's favourite author
  | `band` | `string` | Sets chatbot's favourite band|
  | `book` | `string` | Sets chatbot's favourite book
  | `color` | `string` | Sets chatbot's favourite colour
  | `food` | `string` | Sets chatbot's favourite food|
  | `movie` | `string` | Sets chatbot's favourite movie
  | `opera` | `string` | Sets chatbot's favourite opera|
  | `season` | `string` | Sets chatbot's favourite season
  | `show` | `string` | Sets chatbot's favourite show|
  | `song` | `string` | Sets chatbot's favourite song
  | `sport` | `string` | Sets chatbot's favourite sport|
  | `subject` | `string` | Sets chatbot's favourite subject
  | `football` | `string` | Sets chatbot's favourite football team|
  | `celebrity` | `string` | Sets chatbot's favourite celebrity|
  | `chinesesign` | `string` | Sets chatbot's chinese sign
  | `family` | `string` | Sets chatbot's family|
  | `ethics` | `string` | Sets chatbot's name
  | `etype` | `string` | Sets chatbot's etype|
  | `baseball` | `string` | Sets chatbot's faovourite baseball team
  | `city` | `string` | Sets chatbot's city|
  | `state`| `string` | Sets chatbot's state
  |`class`| `string` | Sets chatbot's class|
  |`country`| `string` | Sets chatbot's country|
  |`company`| `string` | Sets chatbot's company|
  |`email`| `string` | Sets the chatbot's support email|
  |`wechat`| `string` | Sets chatbot's wechat|
  |`wear`| `string` | Sets chatbot's favourite cloth/wear|
  |`vocab`| `string` | Sets chatbot's number of vocabulary|
  |`version`| `string` | Sets your chatbot's version/your bot's version|
  |`totalcli`| `string` | Sets chatbot's total clients|
  |`species`| `string` | Sets chatbot's species|
  |`sign`| `string` | Sets chatbot's sign|
  |`scspecies`| `string` | Sets chatbot's species (chinese)|
  |`scsign`| `string` | Sets chatbot's sign (chinese)|
  |`scnationality`| `string` | Sets chatbot's nationality (chinese)|
  |`scmaster`| `string` | Sets chatbot's master/owner/developer_name (chinese)|
  |`scgender`| `string` | Sets chatbot's gender (chinese)|
  |`scfavouritecolor`|`string` | Sets chatbot's favourite color (chinese)|
  |`scfavouritefood`| `string` | Sets chatbot's favourite food (chinese)|
  |`sccountry`| `string` | Sets chatbot's country (chinese)|
  |`sccompany`| `string` | Sets chatbot's company (chinese)|
  |`sccity`| `string` | Sets chatbot's city (chinese)|
  |`scchinesesign`| `string` | Sets chatbot's chinese sign (chinese)|
  |`language2`| `string` | Sets chatbot's language while chatting|
  |`hockey`| `string` | Sets chatbot's favourite hockey team|
  |`job`| `string` | Sets chatbot's job|
  |`music`| `string` | Sets chatbot's favourite music|
  |`celebrities`| `string` | Sets chatbot's favourite celebrities/characters|
  |`orientation`| `string` | Sets chatbot's orientation|
  |`phylum`| `string` | Sets chatbot's phylum|
  |`president`| `string` | Sets chatbot's president|
</details>
  
  
  
  <h3 id="fetch-user">Discord User Information</h4>
<details>
  <summary> Read More!</summary>
  <br>
  
  ```
  https://aromaxdev.xyz/api/discord/user/<UserID>
  ```
  
  # Example
  
  ```js
  const fetch = require("node-fetch").default;
fetch(`https://aromaxdev.xyz/api/discord/user/519666024220721152`, {
        
    })
        .then(res => res.json())
        .then(data => {
       console.log(data.url) // Gives avatar link
  console.log(data.username) // Gives username 
        })
  ```
  
</details>
