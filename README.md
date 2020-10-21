Quizzler is a webapp developed using React inspired by [this](https://www.youtube.com/watch?v=aq-fCtg_gG4) tutorial at KnowledgeHut.

You can view the fully deployed app at [Quizzler App](https://quizzler-nm.netlify.app) to take randomized quizzes and receive your score.

This app features a hybrid of Class Components and Function Components with local state. The initial questions state is loaded by pulling data from a local API, and then data from the questions is passed down as props to the QuestionBox Component to render reach question and answer options on the page. Finally, after a user has selected 5 answers, the state of the application changes to render the user's score and presents a "Play Again" button which reinitializes all states of questions, score, and responses.

