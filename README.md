# Demo for Branching and Merging (incl. Merge Conflicts)

1. Create a new git repo:
    - Create the folder for the repo and call it something memorable.
    - Use Git or VSCode to initialise and publish the repo.

2. Create a file called `favourites.txt` and enter some of your favourite Foods as follows:
```
Food
- Pizza
- Brocolli
- Donuts
- Chocolate
- Carrots
```

3. Commit and Push the this `main` branch

4. Create a new branch called `drinks`

5. In this branch, add a new section to the `favourites.txt` file containing some of your favourite Drinks, as follows:
```
Drink
- Tea
- Coffee
- Cola
- Liquid Thorium
```

6. Commit the changes to this `drinks` branch.

7. Switch back to the `main` branch and change some of your favourite Foods, as follows:
```
Food
- Calzone
- Brocolli
- Milk Chocolate
- Carrots
- Soup
```

8. Comit the changes to this `main` branch.

9. Switch back to the `drinks` branch and merge the branch into `main` by creating a `Pull Request`.

10. Open the file to view the `Merge Markers`. 
    - To resolve the conflict, edit this file so that it looks like how you want it to look at the end of the merge.
    - Remove the `Merge Markers` and any lines you don't want.
    - Save the file.
   
11. Commit the changes to the merge.

12. You can now delete the branch or keep working on it.
