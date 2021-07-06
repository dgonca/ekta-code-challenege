# Ekta Code Challenge 2021
Thanks for applying to Ekta for the Junior Developer position. Here's a code challenge to make sure that your skills fit into the role we would need you to perform in.
Please fork this repo, answer the questions in the answers.js file included in this repo, push your changes and email us with the repo's url.

Thank you. If you have any questions please email dev@ekta.co.

### #1 What is this code doing? How might it be improved?

`return !this.allQuestions.filter(q =>
            q.subThreadName == this.currentQuestion.subThreadName
          )
          .filter(q => q.mrLevel == this.currentQuestion.mrLevel)
          .some( q => q.currentAnswer == "No")`


### #2 What is this code doing?

`var oldAssessment = this.allQuestions.map( q => Object.assign({}, q));`

### #3 What is this code doing?

`const old = this.allQuestions.map(function(question: any) {
  return {...question};
})`

### #4 I have an array of objects, they are currently untyped. I'm unsure of how but mixed in with my normal objects (`{ id, name, date, createdAt }`), are `null` values. How would you eliminate the null values?

### #5 In Angular 2+ how to you pass variable(s) from a parent to a child? answer in concept

#### code example for #5:

```// file 1.
<div>
  <header-component />
</div>
class FileOne {
...
private date: any;
headerMessage: string;
...
}
// file 2 -- header-component
<div>
  // HERE is where I want a header message
</div>```
