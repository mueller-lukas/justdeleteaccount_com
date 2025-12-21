# JustDeleteAccount.com
A searchable directory helping users discover and delete their unused online accounts. 
In this GitHub repo you can contribute to the website https://www.justdeleteaccount.com/ aswell as to the API data of JustDeleteAccount.com

## What is JustDeleteAccount.com?
JustDeleteAccount.com is a directory of direct links and instructions for deleting accounts from web services. Each service has its own dedicated page, making deletion instructions easily discoverable through search engines like Google, Bing, and Qwant.

## What makes JustDeleteAccount.com different?
**Search Engine Discoverability:** Unlike centralized directories, each service entry has a unique subpage (e.g., justdeleteaccount.com/servicename). This means users searching "how to delete [service] account" can find instructions directly—even if they've never heard of account deletion directories.

**Goal:** Help users discover account deletion instructions through organic search, not just through activly visiting our or a similar directory.

## Why delete old accounts?

New data breaches are announced regularly. Deleting unused accounts reduces your exposure to:
- Data breaches and leaks
- Unwanted marketing and spam
- Privacy violations
- Identity theft risks

## Roadmap

- [x] Transfer repo to new GitHub Account
- [ ] GitHub Action for JSON validation 
- [ ] Website redesign
- [ ] Complete API v1
- [ ] Open-source website code
- [ ] Browser extensions (Chromium based & Firefox)

## How to Contribute

All service data lives in `services.json`. You can:
- Add new services
- Update existing deletion instructions
- Fix outdated information
- Improve descriptions

### Contributing via Git (Preferred)

Submit a pull request with your changes to `services.json`. See the template below for the correct format.

### Contributing via Email

Not familiar with Git? No problem! Send your updates to **webmaster@justdeleteaccount.com** with:
- Service name
- Deletion URL or email
- Step-by-step deletion instructions
- Difficulty level (easy/medium/hard/impossible)

While we prefer Git contributions for faster processing, email submissions are welcome and will be added manually.

## Entry Template
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

## Review Process

1. Submit a pull request with your changes (or email to webmaster@justdeleteaccount.com)
2. A team member will review your contribution
3. Once merged, changes go live on the website and API within 24 hours

## Related Projects

This project shares goals with other account deletion directories like [justdeleteme.xyz](https://justdeleteme.xyz/). We focus on search engine discoverability to reach users who may not know such services exist.
Feel free to inform us about similar services with open-source data sets that we can list here.
