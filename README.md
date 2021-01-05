
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Installation](#installation)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



## About The Project

- Build your Resume with this application , register and login to create your own resume easily.
- Run the program and go to localhost:5000
- Add user details and entries
- Users can add fields 
- Users can also update or delete entries

### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* Flask
* sqlalchemy
* Python

### Installation


1. Clone the repo
```sh
git clone https://github.com/namanbhatia7/IntelliResume
```
2. Enter Directory
```sh
cd IntelliResume
```
3. Install all packages
```sh
pip install -r requirements.txt
```
4. Remove site.db file to start fresh database
```sh
rm resume/site.db
```
5. Setup Env Variables

  create file .env inside folder resume

  Add the following 
```sh
MAIL_USERNAME="{{ your gmail username }}"
PASSWORD="{{ your password }}"
```

6. Run webserver
```sh
python app.py
```

# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. 


## Pull Request Process
1. Ensure any install or build dependencies are removed before the end of the layer when doing a 
   build.
2. Update the README.md with details of changes to the interface, this includes new environment 
   variables, exposed ports, useful file locations and container parameters.
3. Only send your pull requests to the development branch where once we reach a stable point 
    it will be merged with the   master branch 
4. Associate each Pull Request with the required issue number 

## Branch Policy 
* development: If you are making a contribution make sure to send your Pull Request to this branch . All
            developments goes in this branch.
* master: After significant features/bug-fixes are accumulated in development branch we merge it with the master branch.

## Contribution Practices
* Write clear and meaningful commit messages.
* If you report a bug please provide steps to reproduce the bug.
* In case of changing the backend routes please submit an updated routes documentation for the same.
* If there is an UI related change it would be great if you could attach a screenshot 
 with the resultant changes so it is easier to review for the maintainers 

## License

Distributed under the MIT License. See `LICENSE` for more information.

