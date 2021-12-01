# BAG Front-End Coding Challenge

## Brief
Your challenge is to build out a dashboard which showcases a checklist of countries a user plans to travel. Get it looking as close to the design as possible.

You need to use ReactJs/TypeScript to complete this challenge. 

- React : `NextJs` or `CRA`
- React Component Library : `HeadlessUI`, `MUI` or `ChakraUI`
- Database : `MonogoDB`, `PostgreSQL` or any database 
- (Optional) HTML/CSS framework : `TailwindCSS`

## How to Submission
- Create a public/open repository (Gitlab or Github )
- Submit link to repository & your personal details using this google form https://forms.gle/iTuhssFuMimVvsnC6
- Deadline : 10th December at 12:00 pm

## Requirements : Your users should be able to:

View the optimal layout for the app depending on their device's screen size
See hover states for all interactive elements on the page.

### Design assests 

[Desktop Design](https://www.figma.com/proto/zbExDbsTm2NNcLLzfg9mDc/Bag-Challenge?page-id=0%3A1&node-id=2%3A535&viewport=435%2C48%2C0.25&scaling=min-zoom&starting-point-node-id=2%3A535&show-proto-sidebar=1)

[Mobile Design](https://www.figma.com/proto/zbExDbsTm2NNcLLzfg9mDc/Bag-Challenge?page-id=0%3A1&node-id=2%3A971&viewport=435%2C48%2C0.25&scaling=min-zoom&starting-point-node-id=2%3A971&show-proto-sidebar=1)

### Use Icons from

https://heroicons.com/

https://feathericons.com/

### Register/Login
- Register before they use the dashboard
- Login to the dashboard (you can create your own UI/flow)
- Save list of countries
Bonus : Social Login, you can use https://next-auth.js.org if using NextJs

### Dashboard 
- Use REST API https://restcountries.com to get countries data
- Create, Update, Read, Delete from list. (you are only adding/removing from the list)
- Search box to find country and add it to the dashboard.
- Add a country to the travel dashboard. 
- Click country to view full details
- Mark a country as visited.
- Delete a country from the list
- Filter by visited/planning/all countries 
- Delete/Clear all visited countries.


### Object/modal Structure

User Modal:
- Name (First Name, Last Name) 
- Email (Unique) 
- Phone Number
- Date of Birth
- Country 
- Creation Date
- Login Date

## Best practices to follow

- Organized Code, folders, components
- Document/Comment your Code
- Standardized Naming conventions (Folders, files, components)
- Serverless functions (Vercel, Netlify) 
- Form fields validation
- Error handling & logging 
- Env variables : Do not hard code any private or sensitive data
- Create a README.md file with clear instructions on how to Install, Test & Run.

## Bonus

- Toggle light and dark mode
- Drag and drop to reorder items on the list
- Enable application & system logging (errors, actions, login, logout, etc) 
- Testing
    - Integration tests for all your use cases.
    - Write unit tests with a minimum of 60% coverage.
