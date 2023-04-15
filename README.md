# Module-8-assignment
This repository contains my answers to module 8 assignment

QUESTION 1 AND QUESTION 2

Solutions to question 1 and 2 are on the file Node 1 txt.

QUESTION 4

app.get('/user/:name/:age/:sex', (req, res) => {
  const user = {
    name: req.params.name,
    age: req.params.age,
    sex: req.params.sex
  };
  req.user = user;
  res.send('User object added to the request!');
});

QUESTION 5

app.get('/user/:name/:age/:sex', (req, res) => {
  const user = {
    name: req.params.name,
    age: req.params.age,
    sex: req.params.sex
  };
  req.user = user;
  res.json(user);
});

