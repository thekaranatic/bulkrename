# Bulk Rename - Rename multiple files in one go

- A simple Python script to alter the names of every object or file in a folder at once.
- This will be useful in creating a dataset with a large number of objects or items for which custom names may be provided.
- Also useful when you want to sequentially number the files without a name (basename).

## Outcome Preview
![image](https://raw.githubusercontent.com/thekaranatic/bulkrename/refs/heads/main/bulkRename-bg.png)

## Requires:
  - Python
  - Git (Only if you are cloning the repository)

## Usage:
1. Download the repository OR Clone the repository to your local environment/directory:
    ```sh
    $ git clone https://github.com/harsha6602/bulkrename.git
    ```
2. Navigate into the directory you cloned the repo into

3. Run `main.py` file.

4. Enter the path to the folder or copy-paste it, as below:
   > ![image](https://user-images.githubusercontent.com/108540874/182696045-f4eacb62-6e73-45fb-b155-d83e4b84b0ec.png)

5. Before proceeding further, check if the path of the folder and the number of items in it are correct.
   > ![image](https://user-images.githubusercontent.com/108540874/182696696-0ba06d3d-c1d1-433d-a88e-c74f158ea92b.png)
    - If yes, then enter `y`.
    - If not enter `n` and again run the code from the beginning (i.e. double-check your folder path).
      
4. Now enter the **name (basename)** you would like to have for all the files Hit `Enter key` to skip this option if you don't wish to have a basename):
    > ![image](https://user-images.githubusercontent.com/108540874/182691427-8d17bc19-1026-401a-a5cd-16642bcde382.png)
    
   As shown in the figure above,
      - Names will be in the form: `[name]_[number].[fileExtension]`
      - For files with no basename: `[number].[fileExtension]`

6. Finally, enter the index (number) you want to start from:
   > ![image](https://user-images.githubusercontent.com/108540874/182696816-685097b8-954a-45b6-bce2-8553a163444c.png)

7. If you are prompted with the message `successfully changed` then the item names are changed successfully.
