# Digital Hand Cricket


An **interactive webpage** bringing to life, the digital version of the primitive **Hand Cricket game**, created using `HTML`, `CSS`, `JavaScript`, `NodeJS` and `React`.

## Tools and Languages Used :


## Download and Usage :

The code can be downloaded as a compressed `zip` file from the github web interface.

The repository can also be cloned using:

```
git clone https://github.com/Dharani-Eswaramurthi/hand-cricket.git
```

The game can be deployed locally after extraction by opening the folder in the terminal and running the code,

```
npm start
```

The above code opens the webpage on your defaulf browser. The page can also be opened on other browsers by opening the link,

```
http://localhost:3000
```

## Components of Project :

- **JavaScript XML** files - 1
- **CSS** files - 1
- _Note: The above mentioned files are the important additional files added to the default React-App_

## About the Webpage :

The Webpage contains **multiple pages** that represent various phases of the game. Each page is actually a `div` tag being displayed while the other remain **hidden**. The deployment of each page is managed by various `function` of the `class`. The `algorithm` provides a smooth flow to the game, providing a _user friendly interface_. The various components of the program are explained below:

- **Home** :

  - The home page of the game provides a simple layout allowing the user to call for the toss.
  - Tossing is executed **unbiased** with the help of a modified **random** function.
  - The decisive call of the user for toss takes the user to further pages using a sequence of **_function calls_** and \*_conditional statements_.

- **Election** :

  - Result of the **unbiased toss** is displayed in a seperate page.
  - A fair chance is provided for both the computer and the player to win the toss.
  - The **random** function is brought to use again if the computer wins the toss inorder to choose between **batting** and **bowling**.
  - On the other hand, the user is allowed to choose between batting and bowling on winning the toss.

- **GamePlay** :

  - The gameplay page enables the user to choose numbers between 1 and 6 similar to the _primitive physical version_.
  - The **scores** of the computer and player are update instantly while **rendering** the page.
  - The page also displays the previous calls made by the user and the computer to help take a **stochastic decision**.
  - The **status** of the user and the **target** are also updated to trigger the enthusiasm.

- **GameOver** :

  - The game contains multiple terminal pages which will be invoked based on the result.
  - The game also offer a seperate page which says out, representing the end of the first innings.

- **Graphical Features** :

  - The project contains **multiple graphical content** ranging from _bending of borders_ to _styled fonts_ and _eye-soothing layout_.
  - The `CSS` file checks in all the requisites for empowerment of the graphical interface.

- **JavaScript** :
  - The `JavaScript` plays the most significal role, driving the entire game.
  - The **precise algorithm** of the game manages the flow controlling everything from **function calls** to **page switches** and **score calcutions**.
  - The `algorithm` is built using simple `conditional statements`,`functions` and `classes`.

### Suggested Browsers for Deployment :

- Microsoft Edge
- Google Chrome
- Safari
