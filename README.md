# Questgen

## 📌  Introduction
Questgen creates questions and answers based on your document.

**Type of questions:**

✅ True/False question <br>
✅ Multiple choice question <br>
✅ Fill in blank question <br>

**Level of questions:**

✅ Easy <br>
✅ Medium <br>
✅ Hard <br>

## 🎬  Demo
**True/False question**
- Easy
- Medium
- Hard
  
**Multiple choice question**
- Easy: <br>
  Question: What is Object Oriented Programming? <br>
  Options: <br>
    A programming pattern where programs are structured around objects <br>
    A programming pattern where programs are structured around functions <br>
    A programming pattern where programs are structured around logic <br>
    A programming pattern where programs are structured around data <br>
  True option: A programming pattern where programs are structured around objects <br>
- Medium: <br> 
  Question: What does Abstraction help in? <br>
  Options: <br>
    Data hiding process <br>
    Displaying essential features without showing details <br>
    Avoiding unnecessary information or irrelevant details <br>
    All of the above <br>
  True option: All of the above <br>
- Hard: <br>
  
**Fill in blank question** 
- Easy <br>
  Question: OOPs stands for Object Oriented __________ C++. <br>
  Options: <br>
      a) Programming <br>
      b) Polymorphism <br>
      c) Inheritance <br>
      d) Abstraction <br>
  True option: a) Programming <br>
- Medium: <br>
  Question: Abstraction allows hiding __________ implementation details and exposing a simplified interface to the user. <br>
  Options: <br>
      a) complex
      b) unnecessary
      c) irrelevant
      d) essential
  True option: a) complex <br>
- Hard: <br>
  Question: Inheritance establishes a __________ relationship among classes, reflecting real-world or conceptual hierarchies. <br>
  Options': <br>
      a) hierarchical
      b) polymorphic
      c) encapsulated
      d) abstract
  True option: a) hierarchical <br>

## 🚀  Quickstart
```bash
# clone project
git clone https://github.com/ctpanh/Questgen.git
cd Questgen

# [OPTIONAL] create conda environment
conda create -n myenv python=3.9
conda activate myenv

# install requirements
pip install -r requirements.txt
```


## 🌐  Main Technologies
- Frontend:
- Backend:
- AI: OpenAI

## 📎  Project Structure

The directory structure of new project looks like this:

```

├── client                   <- Frontend
│   ├── .vscode                  <- vscode file
│   ├── public                   <- Bo cai nay di
│   └──  src                     <- Source code
|         ├── assets                 <- 
│         ├── components             <- 
│         ├── router                 <- 
│         ├── store                  <- 
│         ├── view                   <- 
│         ├── App.vue                <- 
│         └── main.js                <- 
├── server                   <- Backend
    ├── core                      <- Core part to generate questions
    |    ├── article.txt             <- Document to generate questions
    |    ├── generate_questions.py   <- Generate questions
    |    ├── handle_input.py         <- Handle long input file
    |    └── prompt.py               <- Prompt to ask OpenAI
    ├── questgen                     <-
    └── server                       <-

```
