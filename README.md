# README

FreeDoc - Réserve ton docteur 


Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite


2.1. FreeDoc - Réserve ton docteur
2.1.1. Le pitch



    un model Doctor, qui a comme attributs :
        un first_name, qui est un string
        un last_name, qui est un string
        un specialty, qui est un string
        un zip_code, qui est un string
    un model Patient, qui a comme attributs :
        un first_name, qui est un string
        un last_name, qui est un string
    un model Appointment, qui a comme attributs :
        un date, qui est un datetime

Une fois les attributs fixés, on s'attaque aux relations :

    Un appointment ne peut avoir qu'un seul doctor, mais un doctor peut avoir plusieurs appointment.
    Un appointment ne peut avoir qu'un seul patient, mais un patient peut avoir plusieurs appointment.
    Un doctor peut avoir plusieurs patient, au travers des appointments, et vice versa.
    
A la fin il faut ajouter la table City dont les autres tables auront une rélation 1xN
