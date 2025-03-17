# helmet_detection

This is a Jupyter Notebook that can detect whether someone is wearing a helmet or not.
The program allows you to take an image to test with using your webcam

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

- Webcam needed to 'see' the helmet
- Jupyter Notebook to run the model

### Installing

- Install the JRE (Java Runtime Enviroment) onto your computer
- Install MySQL onto your computer - set username and password to root (if you have mySQL already with different login details you need to change these in src/main/resources/db.properties AND src/main/resources/db.properties
- Edit your system enviroment variables to add MySQL to your system - https://dev.mysql.com/doc/mysql-windows-excerpt/5.7/en/mysql-installation-windows-path.html
- Open your command line and run mySQL - "mysql -u root -p" (replace root with username if you have different details)
- In these files, navigate to src/main/resources and select sql-schema.sql
- Create the database from this file

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Deployment

This will run locally through Jupyter Notebooks. Alternatively, you could use Google Colab.

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

This project is licensed under the MIT license - see the [LICENSE.md](LICENSE.md) file for details 

*For help in [Choosing a license](https://choosealicense.com/)*

## Acknowledgments
