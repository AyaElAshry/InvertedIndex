# InvertedIndex using **Binary Search Tree** data structure

This project based on the Binary Search Tree data structure
![screenshot1](https://user-images.githubusercontent.com/64116564/83792294-dd6ded80-a668-11ea-9e2a-c346450bf62b.png)

Each word is a **node** that stores data needed for each word in the BST  
`struct node  
    {   
    QVector<int> index;   
    int document_number;   
    QString word;   
    node *left;   
    node *right;   
    }`   
    


* To use th simulation, you should first copy **the directory** where the files -you want to insert- exist in the directory linetext,,  
Afterwards press on "OK" button.  

![d1](https://user-images.githubusercontent.com/64116564/83793493-9d0f6f00-a66a-11ea-83c5-12ba0326de2e.png)

* After pressing the **insert** button, Every word in every file will be inserted in a BST.  
**Note:** the Complexity of insertion is **O(log(n))** assuming **Balanced BST** & **O(n) assuming **Skewed BST**  
while the Complexity of building the whole BST is **(O(n*log(n))** assuming **Balanced BST** & **O(n^2) assuming **Skewed BST**.  
So, this may take a few minutes for a very large number of files to be completed 'n indicates the number of words'. 

![d3](https://user-images.githubusercontent.com/64116564/83795461-7bfc4d80-a66d-11ea-8c0f-bcadf8449559.png)

* To **Search** for a certain word you only have to insert it & press on "Search" button.  
**Note:** the Complexity of searching is **O(log(n))** assuming **Balanced BST** & **O(n) assuming **Skewed BST**.  

![d2](https://user-images.githubusercontent.com/64116564/83796152-8b2fcb00-a66e-11ea-9673-c639a696bbf1.png) 

* To delete the tree, you only have to press "Reset" button and the whole data will be gone.  
**Note:** the Complexity of deletion is **O(n)** where n is the number of words.
