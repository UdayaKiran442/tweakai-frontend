# Folder Structure

## api
- index.ts will have code to create an instance which connects frontend with backend
- individual folders must be created for each api service, for example auth.ts for auth api's, etc

## assets
-  will have all images, svg's, pdf and other static files

## components
- will have all reusable components in the code

## pages
- will have pages connected to react router

## services
- will have code when using external services via their api
- for example openai service can be written in this folder

## utils
-  will have code for reusable functions

## React-Redux for state management
- Configure redux for state management

# Github guidelines
- Maintain two branches one for production(main) and other for development
- While creating a new feature create a branch from development with name FEATURE-feature-name
- If solving a bug create a branch from development or main which as per requirement with name FIX-bugname
- Frequently commit the code. Commit message must be in present tense. For example while pushing after fixing a bug commit message must be FIX-message where as while pushing a feature commit message must be FEATURE-message.
- If there is a code change in refactoring or cleaning of code then commit message must be CHORE-message
## Type of commit messages
- FEATURE - a new feature is introduced with the changes
- FIX - a bug fix has occurred
- CHORE - changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies or refactoring code)
- DOCS – updates to documentation such as a the README or other markdown files

## Example commits
- FEATURE: improve performance with lazy load implementation for images
- CHORE: update npm dependency to latest version
- CHORE: code clean up and build 
- FIX: bug preventing users from submitting the subscribe form
- INIT: Only for first commit and project setup