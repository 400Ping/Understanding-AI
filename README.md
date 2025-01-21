# Hanyang University ERICA-Understanding of AI

## Links

### Important Links

 - [Jupyter](https://jupyter.org/)
 - [Syllabus](./Resources/00-Course%20Introduction.pdf)

## Lab 2 Hello world AI

 - [Problem](./Lab2/02%20Lab%20-%20Hello%20world%20AI.pdf)
 - [Code](./Lab2/Lab2.ipynb)
 - [Datasets](./Lab2/)

 ## Lab 4 Regression and Clustering

 - [Problem](./Lab4/04%20Lab%20-%20Regression%20and%20Clustering.pdf)
 - [Code](./Lab4/Lab4.ipynb)

 ## Lab 5 Neural Network

 - [Problem](./Lab5/05%20-%20Neural%20Network.pdf)
 - [Code](./Lab5/Lab5.ipynb)
 - [Datasets](./Lab5/Student_performance_data%20_.csv)

 ## Lab 6 Deep learning classifier

 - [Problem](./Lab6/06%20Lab%20-%20Deep%20learning%20classifier.pdf)
 - [Code](./Lab6/Lab6.ipynb)

 ## Lab 7 Tic Tac Toe

 - [Problem](./Lab7/07%20Lab%20-%20Tic%20Tac%20Toe.pdf)
 - [Code](./Lab7/Tic%20Tac%20Toe.ipynb)

 ## Lab 8 Final

 - [Report](./Final/AI-Final_Report.pdf)
 - [Code](./Final/Final.ipynb)
 - [Datasets](./Final/Student_performance_data%20_.csv)

## Some Github Commands

* Remember to save and git add, git commit before doing further operations

1. upload

    ```shell
    git add .
    git commit -m "your comments"
    git push
    ```

2. download

    ```shell
    git checkout <branch>
    git fetch
    git merge
    ```

3. new branch

    ```shell
    git checkout -b <branch>
    ```

4. switch branch

    ```shell
    git checkout <branch>
    ```

5. delete a local branch

    ```shell
    git branch -d <branch> # for merged branches
    git branch -D <branch> # force deleting
    ```

6. delete a remote branch

    ```shell
    git push origin --delete <remote branch>
    ```

7. merge branch

    ```shell
    git merge <branch to be merged>
    ```

8. bring back deleted files
   
   ```shell
   git checkout <PREVIUS COMMIT> -- .
   git add .
   git commit -m "Restore all deleted files"
   ```