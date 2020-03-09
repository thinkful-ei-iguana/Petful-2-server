# Pawsibilities
Petful assignment, built by Anugrah Lambogo and Maggie McClellan

Cat and dog lovers, gather 'round! The newest member of your family can't wait to meet you. Pawsibilities is a web app that allows users to adopt a cat or dog (*disclaimer: this is all virtual; no actual adoptions are available through this site!). Join the queue of hopeful adopters, and when it's your turn, click on a dog or cat to select the pet you'd like to take home.

## Visit Pawsibilities
[Live app](https://pawsibilities-v2.now.sh/ "Pawsibilities")

[GitHub repository (client)](https://github.com/thinkful-ei-iguana/Petful-2-client "Pawsibilities client repo")

## Technology used

**Front-End:** *ReactJS | CSS*

**Back-End:** *NodeJS | ExpressJS*

**Testing:** *Mocha | Chai*

## API Documentation

| **HTTP Verb** | **Path**                           | **Used for**         |
| --------- |:--------------------------------------:| --------------------:|
| GET       | /cats | return all available cats     |
| GET       | /dogs  | return all available dogs    |
| GET       | /humans  | return all humans in line to adopt    |
| DELETE  | /cats   | remove dog from front of line (adds same dog to the back of the line) |
| DELETE | /dogs | remove dog from front of line (adds same dog to the back of the line) |
| DELETE | /humans | remove human from the front of the line (adds to the back of line)|
| POST | /humans  | adds user to the back of the line  |


