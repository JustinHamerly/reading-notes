# Class 14 - Authentication

[Home](https://justinhamerly.github.io/reading-notes/)

---

## **OAuth**

sourcce: [CSO Online](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

**What is OAuth?**

A secure, third-party authorization protocol

**Give an example of what using OAuth would look like.**

When you go to a website, you can log in with another website.  You use permissions from another site to log into one site.

**How does OAuth work? What are the steps that it takes to authenticate the user?**

verify identity from another website, you are given a one time token for logging on, token is used by the first site, the software presents its token to the authorization provider, authentication approval request, approval from user, user given an access token, access token given to the website, first website gives token to second website, successful transation

**What is OpenID?**

it is an authentication tool for people, whereas OAuth is an authorization tool.

## **Authorization and Authentication Flows**

source: [Auth0 Docs](https://auth0.com/docs/authorization/flows)

**What is the difference between authorization and authentication?**

Authorization gives you access by requesting another source to verify your identity.  Authentication is a way for people to log in directly without the 2nd source.

**What is Authorization Code Flow?**

It is the steps in which authorization happens under the hood.

**What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**

It's a way of authorizing access using code verifiers and   challenges.

**What is Implicit Flow with Form Post?**

instead of using URL fragments for connecting, it uses POST.

**What is Client Credentials Flow?**

Authorization using ID and secret token.

**What is Device Authorization Flow?**

Authorization using a device and getting a code.  First the user has to have an authorized device, then the browser will mark the device as authorized which grants the access token.

**What is Resource Owner Password Flow?**

user logs in with username and password, and info is storedin the backend.  This requires trusted security.

