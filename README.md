# JustDeleteAccount.com
In this GitHub repo you can contribute to the website https://www.justdeleteaccount.com/ aswell as to the API data of JustDeleteAccount.com

# What is JustDeleteAccount.com?
JustDeleteAccount.com is a directory of links where you can delete your account from web services.

# Why should I delete my old accounts?
New data breaches become known every day. Therefore you should delete unused accounts and protect your privacy.

# ToDo List:
- [x] Transfer repo to my new GitHub Account
- [ ] GitHub Action for JSON-Validation 
- [ ] Rework of the JUstDeleteAccount.com website
- [ ] Finish the JustDeleteAccount.com API
- [ ] Open-Source release of the website code
- [ ] Chrome Plugin
- [ ] Firefox Plugin

# How can I contribute?
In the file services.json you can find the data that is used by justdeleteaccount.com.
There you can update and add entries.

# Template
The structure of every entry is as following:<br>
The file is in the JSON format.

```json
         {
            "name":"ExampleService",
            "deleteurl":"https://exampleservice.com/account/deletion",
            "deletemail":"remove@exampleservice.com",
            "difficulty":"easy",
            "description":"Go to 'Profile > Delete My Account' and select why you are deleting your account.",
            "domain":"exampleservice.com,exampleservice.us"
         },
```
**Difficulty:**  
`easy` - Simple process  
`medium` - Some extra steps involved  
`hard` - Cannot be fully deleted without contacting customer services  
`impossible` - Cannot be deleted  

**Deleteurl and Deletemail:**  
If exists use `"Content"`, else `"deletemail":null,` and/or `"deleteurl":null,`

# How long until a change takes effect?
After you created a pull request one member of our team will review it.  
After the change is added to the master branch, it will be automatically used by the website and the api within 24h.
