# How we worked on the Bank Account Manager App.

 This project is about how to create, retrive, edit and delete bank accounts. First we frok and clone our 
project from github with git on to our local repo and run yarn install to add the dependencies then we opened the code in our text editor. 
Secondly, we created a new brunch for our project and run yarn add react redux, bulma and commited all the necessary changes.
Then we yarn start the project to see if its works as expected. We created an actions, Reducer and store folders in our src and 
created the needed files inside the folders (actionAccount.js, accountReducers.js and store.js). 

We first focus on the create and retrive part to display the items. In doing that we worked with the store.js and actionReducer.js
then the index.js to wrap Provider with store as props around the rendered component. We imported connect from react readux and added
mapDispatchToProps and mapStateToProps to were it needed to connect the component to the redux.
Then we wrote the actions for the create and retrive and the edit and delete in actionReducer.js and actionAccount.js to get them to work.



/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

# Bank-account-manager-react
The purpose of this project is to test your understanding on all the concepts we've covered so far in the React and Redux classes.
It will also put your git skills to test as you'll be collaborating with a partner using git.

## project summary
Bank account manager app bootstraped with Create React App that has full CRUD functionality for
- Adding accounts
- Seeing all accounts added
- Editing accounts
- Deleting accounts

This repository already has all the boilerplate with the UI developed. However none of the full functionalities are working yet. Your job is to complete 
all the CRUD functionality using react redux for shared state management.

## instructions
- Fork your own copy of the repo
- Clone the repo locally
- Run yarn install (or npm install) to install project dependencies
- Open project in your text editor
- Create a new branch where you'll commit your changes
- Go through the codebase to get familiar with the code and how each component is connected together
- Make sure that you have a clear idea of the flow and how the app is supposed to work. Ask questions to get clarity.
- Complete the CRUD features using React and Redux.
- Commit your changes each step of the way.
- Test your work to confirm that it works as expected.
- Deploy your work and add the link to the ReadMe.
- Update the ReadMe to outline the steps you took to make the app work.
- Push your work to Github.
- Submit a pull request to the main repo: https://github.com/codetrainafrica/contact-manager-react/
