# RaphaelSOMADIT
A DIT SOMA API for capturing student information


use pip install RaphaelSomaDIT to install the package

use the rex instance to access the methods


import RaphaelSomaDIT import rex

the instance has 3 methods up to this stage
1. The studentImage which require two parameters the Email and Password,
2. The studentInfo which also require two parameters the email and password
3. The third is a result which this will be done on v0.03

1. the Student image only have a single parameter which is photo so to access you have to call the parameter photo
 => rex.photo

2. the student information has 10 variables

    >> regno 
    >> gender
    >> dob
    >> email
    >> mobile
    >> martial_status
    >> academic_year
    >> NTA_level
    >> name
    >> nationality

so to access any of that you have to call using an instance rex


=> rex.regno to obtain the registraction number

HOW TO USE

#import required library


from RaphaelSomaDIT import rex

#...............to obtain student details........................#

rex.studentInfo('<<your valid Email>>','<<Your Valid Password>>')
 

rex.name #this return full name of the student


THANK YOU 😎

     
