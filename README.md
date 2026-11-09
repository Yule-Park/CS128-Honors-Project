# CS128-Honors-Project
Group Name: CS 128 honors group 1
Names: Andrew, Yule
NETIDs: ak167, yulep2
Project introduction: 
Our project is a command-line interface that will allow users to submit solutions to contest problems from their terminals. Currently, users have to switch between their coding environment and the online contest platform, but our project will make it so that they can submit contest solutions and view results without having to do so. We have chosen this project because we're lazy and don't want to switch between our coding environment and the contest website anymore. 
Technical overview: 
We will use the clap crate to parse commands entered by users, reqwest to make HTTP requests to online judges, and thiserror to handle errors. 
By the first checkpoint, we plan to select a platform to support, implement basic commands using clap, and implement functions to read and validate local source files.
By the second checkpoint, we plan to implement HTTP communication with reqwest, implement the submission process for source code files, and work out how to display judge results. 
Challenges: 
Some potential challenges are learning rust crates such as thiserror and working out how to handle authentication with our select online judge. We will also need to find out a way to handle errors and figure out a way to display helpful error messages. 
References:
https://github.com/skygragon/leetcode-cli
https://github.com/kidskoding/spotify-cli
https://github.com/jshaughnessy24/project_cs128h
