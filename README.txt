TOBY CROCKER
CSCI 404
PROJECT 03 POSTERIOR PROBABILITY

TO COMPILE:
    This code has been tested and runs on Isengard.
        1. navigate to directory containing .zip file
        2. scp <filename>.zip <username>@isengard.mines.edu:
        3. unzip <filename>,zip
        4. Navigate into unzipped project directory 
        5. Type 'make' to compile


RUN:
    Run this program from the command line with the following command, 
    where <observations> is a string of 'C' and 'L' characters (case insensitive)

        ./compute_a_posteriori <observations>

    The program will output the posterior probablilty of each hypothesis to a
        'results.txt' file, after the given string of obserations, 
        as well as the respective probabilities of the next flavor of candy to
        be drawn.
