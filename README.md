# sm-webdev-Speech2txt-task4

## Description

Task4 week3: create a web application that allows users to convert spoken words into text using the Web Speech API. The transcribed text is displayed on the webpage and saved to a MySQL database. 

## Features

- Real-time speech-to-text conversion.
- Saves transcriptions to a MySQL database.

## Demo

https://github.com/Shumokh1/sm-webdev-NLP-task4/assets/151425117/b5327ab6-b228-4c13-8f78-e819ded1c072

## Database Setup

1. Create the `robot2` database:

    ```sql
    CREATE DATABASE robot2;
    ```

2. Switch to the `robot2` database:

    ```sql
    USE robot2;
    ```

3. Create the `transcripts` table:

    ```sql
    CREATE TABLE transcripts (
        id INT AUTO_INCREMENT PRIMARY KEY,
        transcript TEXT NOT NULL
    );
    ```
