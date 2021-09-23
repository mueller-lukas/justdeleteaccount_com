# JustDeleteAccount.com
In this GitHub Project you can contribute to the Website https://www.justdeleteaccount.com/ aswell as to the API data of JustDeleteAccount.com

# What is JustDeleteAccount.com?
JustDeleteAccount.com is a directory of links where you can delete your account from web services.

# Why should I delete my old accounts?
New data breaches become known every day. Therefore you should delete unused accounts and protect your privacy.

# How can I contribute?
In the file services.json you can find the data that is used by justdeleteaccount.com.
There you can update and add entries.

The structure of every entry is as following:
The file is in the JSON format.

```json
         {
            "name":"SomeServiceName",
            "deleteurl":"https://somewebsite.com/profile/account",
            "deletemail":"support@somewebsite.com",
            "difficulty":"easy",
            "description":"Go to 'Profile > Delete My Account' and select why you are deleting your account.",
            "domain":"somewebsite.com,domain2.com"
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
