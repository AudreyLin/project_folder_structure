## Project Folder Structure

This is a sample of how to keep your React and Node project folder structures.

It might change later, but right now its just a quick reference based on some youtube videos I came across.

## Resources

- [WebDevSimplified YT: Junior vs Senior React Folder Structure - How To Organize React projects ](https://youtu.be/UUga4-z7b6s)

## Notes

Have an index.js file in each folder to export and import specifically from that
file for easier maintenance. This is to encapsulate all the logic for those
features from one single location and makes it easier to make changes to the
features.

## Hooks, lib, utils

These folders will only contain hooks that are global that can be used across
the entire app.
