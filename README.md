## Project Folder Structure

This is a sample of how to keep your React and Node project folder structures.

It might change later, but right now its just a quick reference based on some youtube videos I came across.

## Resources

- [WebDevSimplified YT: Junior vs Senior React Folder Structure - How To Organize React projects ](https://youtu.be/UUga4-z7b6s)
- [PedroTech YT: Folder Structure for API's](https://youtu.be/oNlMrpnUSFE)

## Notes

Have an index.js file in each folder to export and import specifically from that
file for easier maintenance. This is to encapsulate all the logic for those
features from one single location and makes it easier to make changes to the
features.

## Hooks, lib, utils

These folders will only contain hooks that are global that can be used across
the entire app.

## Dotenv & Environment variable security

Environment variables should be outside the React folder and inside the Node folder for security purposes.  Also, if you are doing a frontend only project, the enviroment variables and the code to access the environment variables should be written in a backend server (pretty much a fullstack project).  If you write the dotenv access in the src folder of the react/frontend, then they will be accessible to the browser, defeating the purpose of the dotenv and exposing any sensitive api keys, data, etc.  