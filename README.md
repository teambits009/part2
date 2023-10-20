# part2

-- Create the C2C Codebook database
CREATE DATABASE C2C_Codebook;

-- Use the C2C Codebook database
USE C2C_Codebook;

-- Create a table for the survey data
CREATE TABLE SurveyData (
    ID INT PRIMARY KEY,
    First INT,
    Hear_instructor INT,
    Hear_poster INT,
    Hear_socialmed INT,
    Hear_gcwebsite INT,
    Hear_blackboard INT,
    Hear_friends INT,
    Hear_campusprom INT,
    Hear_previous INT,
    Hear_other TEXT,
    Access INT,
    Variety INT,
    Atmosphere INT,
    Experience INT,
    fulltime INT,
    Coop INT
);

-- Insert a sample record into the SurveyData table
INSERT INTO SurveyData (ID, First, Hear_instructor, Hear_poster, Hear_socialmed, Hear_gcwebsite, Hear_blackboard, Hear_friends, Hear_campusprom, Hear_previous, Hear_other, Access, Variety, Atmosphere, Experience, fulltime, Coop)
VALUES (1, 1, 1, 2, 1, 1, 2, 1, 2, 'Radio', 3, 4, 5, 2, 4, 3);
