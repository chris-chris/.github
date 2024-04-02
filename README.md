
# Repositories: 
- Service
- Purpose
- Language
- External Integration
- Database
- Infrastructure
- Main contributor

## org: ubiquibot

### 1. ubiquibot/conversation-rewards
- Service: Conversation Reward Module
- Purpuse: This is intended to be the proper implementation of comment incentives, based on our learnings from the first go-around.
- Language: TypeScript
- External Integration: Github Action, Github API
- Database: None


### 2. ubiquibot/permit-generation
- Service: Permit Generation module
- Purpuse: The purpose of this module is to isolate the bot's payment capabilities. This can be directly invoked from other plugins
- Language: TypeScript
- External Integration: ENS
- Database: Supabase
- Main contributor: @Keyrxng, @pavlovcik

### 3. ubiquibot/assistive-pricing
- Service: Assistive Pricing module
- Purpose: **Don't know**
- External Integration: 
- Database: Supabase

### 4. ubiquibot/comment-incentives
- Service: Comment Incentives module
- Purpose: Split reward to the collaborators who wrote some comments
- Language: Typescript
- External Integration: 
- Database: None (Supabase, TODO: get the assignee multiplier from the database)

### 5. ubiquibot/plugins-wishlist
- Serivce: not a service
- Purpose: Wishlist of the future plugins

### 6. ubiquibot/configuration
- Service: not a service
- Purpose: Helpers to parse and merge configuration files for Ubiquibot.

### 5. ubiquibot/e2e-tests
- Service: not a service
- Purpose: Use this for end-to-end tests.
@pavlovcik How does it work?

### 6. ubiquibot/sandbox
- Serivce: Sandbox Environment
- Purpose: This is a sandbox environment for new users to try out the bot.
  - Try setting one Priority and one Time label to see the assistive pricing capabilities.
  - Try the bot commands as a comment in an issue.

### 7. ubiquibot/production
- Service: Production Environment
- Purpose: ubiquibot production environment
- Language: Typescript
- External Integration: 
- Database: None

## org: ubiquity

### 1. ubiquity/devpool-directory
- Service: DevPool - Bounties Directory
- Purpose: DevPool open bounties. Subscribe to notifications to see new available bounties.
- Database: None (TODO: post to database)
- External Integration: 


### 2. ubiquity/pay.ubq.fi
- Service: Generate and claim spender permits (EIP-2612)
- Purpose: Tool for generating offline permits for bounty hunters to withdraw their payments.


### 3. ubiquity/ubiquity-dollar
- Service: Ubiquity Dollar (uAD) smart contracts and user interface.
- Purpose: Introducing the flagship product of Ubiquity DAO. The Ubiquity Dollar (uAD) is a collateralized stablecoin.
- Language: Typescript, Solidity
- External Integration: Ethereum

### 4. ubiquity/cloudflare-deploy-action
- Service: Cloudflare deploy action
- Purpose: A reusable, and automatic Cloudflare deploy for instant previews across @ubiquity repositories.
- Language: TypeScript
- External Integration: Github Action

### 5. ubiquity/work.ubq.fi
- Service: User interface
- Purpose: A user interface for https://github.com/ubiquity/devpool-directory/issues


### 6. ubiquity/ubiquibot
- Service: Ubiquibot
- Purpose: Ubiquity DAO's GitHub Bot for Automating DevPool Management.
  - Main repo for the bot development.
- Database: Supabase
- 

### 7. ubiquity/ts-template
- Purpose: A template repository for all @ubiquity projects.
- Language: Typescript

### 8. ubiquity/rpc-handler
- Purpose: RPC Handler NPM Package


### 9. ubiquity/onboard.ubq.fi
- Purpose: Generates the configuration for organizations, by creating a default configuration and creating a repository under the given Organization.


### 10. ubiquity/ubiquibot-kernel
- Purpose: Interface with plugins (GitHub Actions) for longer running processes. Run on Cloudflare Workers.
- Infrastructure: Cloudflare Workers


WIP

```
Services: 
- Any internal or external services your system interacts with.

Databases: 
- The types of databases used and their relationships to other components.

External Integrations: 
- Third-party services or APIs your system relies on.

Infrastructure: 
- The underlying infrastructure, such as cloud services, container orchestration (e.g., Kubernetes), and network architecture.
```