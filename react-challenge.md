### App description

Create a simple ReactJS app that fetch and display a list of github issues. For each item display the id and the title. `ul` and `li` should be sufficient to display this list. 

The API supports pagination, at the beginning load the first page with 5 issues. At the bottom there is a button `Next` that loads the next 5 issues. 

Clicking on an issue item to highlight it. Click on it again will toggle the highlight. Only 1 item is highlighted at a time. 

Wall feed and notifications: use redux to store the 5 most recently highlighted issues. Showa list of recently highlighted issues and a notification counter for recently highlighted issues.

Feel free to implement the UI your own way. However we'll pay attention to code quality, and how neatly you implement it. 

### API

This is the endpoint to fetch issues, it's publicly available, no need to authenticate. 

https://api.github.com/repos/rails/rails/issues?page=1&per_page=5

This is the `fetch` method to use for the api call, no need for jQuery. 

https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch

### Deliverables

__A GitHub project__

- README.md: describes dependencies, how to set up, how to run and any other additional information you may want to share. Create a technical decision section and answer the following questions:
  - How did you implement styling? What are the pros and cons? Why did you chose this approach? 
  - How did you share state between components?  What are the pros and cons? Why did you chose this approach? 
  - Did you use React hooks? Why or why not?
- Clean code: don’t over engineer but make your code as readable as it needs to be.
- Build file

Email herve@quod.ai with the URL to your GitHub repo.

## Evaluation metrics ##

- Code quality and clarity
- Clean folder structure
- Simple but suitable design
- Meaningful variable names and functions
- Meaningful commits (not too big, not too small)

### ReactJS resources

Follow the instruction here https://facebook.github.io/react/docs/installation.html . Starting a new react project is as simple as: 

```
npm install -g create-react-app
create-react-app hello-world
cd hello-world
npm start
```

ReactJS state and life cycle can be found here https://facebook.github.io/react/docs/state-and-lifecycle.html 

### Credit

@khacanh
