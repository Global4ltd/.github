## Description
**Linked Issue:** @{{github.head_ref}}<!-- Replace with issue number -->  
[![View in Jira](https://img.shields.io/badge/View_in-JIRA-blue?style=for-the-badge)](https://your-jira-instance.atlassian.net/browse/@{{ github.event.pull_request.title }})

<!-- Provide a summary of the changes. -->  

## Checklist  

### ✅ Developer: @{{ github.actor }}
- [ ] **ESLint** passes with no errors/warnings  
- [ ] **Prettier** formatting applied  
- [ ] Check **Dependabot alerts** – no unresolved high/critical vulnerabilities  
- [ ] No hardcoded **secrets** (API keys, credentials, etc.)  
- [ ] **Dependencies** reviewed for security vulnerabilities  
- [ ] No sensitive data is **exposed** (logs, errors, responses)  
- [ ] **Authentication** & **authorization** checks verified  
- [ ] Secure **error handling** in place (no detailed error leaks)  

### 🔍 QA Reviewer: @{{ github.event.pull_request.requested_reviewers }} 
- [ ] Code changes align with **security best practices**  
- [ ] No sensitive data is being **logged or exposed**    
- [ ] Security vulnerabilities in dependencies checked
- [ ] No **unresolved high/critical vulnerabilities** before approving  
- [ ] No unintended **scope changes or access level modifications**  

## Deployment Considerations  
- [ ] Rollback plan in place
- [ ] UAT stakeholder notified

## Additional Notes  
<!-- Any other relevant information for the reviewer. -->  
