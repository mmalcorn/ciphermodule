## Cipher
Converts a phrase into a simple code.

## By Meredith Alcorn

## Description
This application uses a custom module and hook_form to create a form with the aim of taking in a user's phrase and encrypting it.
Based off of the "direction" value entered into the form, the letters of that phrase will be shifted either forward or backward from the position they hold in the alphabet--left will move the letters backward; right will move the letters forward.  The "value" integer that is entered will move the letters in the phrase that value from their current position.

## Specifications
---------------------------------------
* Input:
---------------------------------------
        Value: 5
        Direction: right
        Phrase: ABCD
---------------------------------------
* Output:
---------------------------------------
        FGHI
---------------------------------------
* Input:    
---------------------------------------
        Value: 1
        Direction: right
        Phrase: Meredith
---------------------------------------
* Output:
---------------------------------------
        Nfsfijui
---------------------------------------
* Input:
---------------------------------------
        Value: 4
        Direction: left
        Phrase: Smashing
---------------------------------------
* Output:
---------------------------------------
        Oiwodejc
---------------------------------------

## Setup/Installation
* Clone this repository
* Point MAMP/WAMP to this folder (ciphermodule)
* Import the latest version of the database - located in dbbackup
* Create the privileges for this database
    username: cipher
    password: cipher
* This should allow you to visit your local host to view the page

## Bugs
* No known bugs.

## Technologies Used
* Drupal 7.52
* MAMP
* phpMyAdmin
* PHP
