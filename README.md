<h1 align='center'><samp><strong>Sorting Algorithm Visualizer</bold></samp></h1>

A sorting algorithm visualizer is like a colorful playground for numbers. You can watch as the numbers race, swap, and line up in perfect order, all with just a few clicks. It’s simple to use and fun to watch, turning complex code into an easy-to-follow animation. Whether it’s a slow bubble sort or a fast quicksort, each algorithm has its own unique style, making the whole process both entertaining and educational. Just sit back, relax, and enjoy the show as the numbers sort themselves out in a visually appealing way!

 Try this impresive tools and enjoy [Try Sort](https://sortxtools.netlify.app/)

## Technology
 ![Html](https://img.icons8.com/?size=100&id=20909&format=png&color=000000)![Css](https://img.icons8.com/?size=100&id=21278&format=png&color=000000 )![JavaScript](https://img.icons8.com/?size=100&id=PXTY4q2Sq2lG&format=png&color=000000)![Bootstrap]( https://img.icons8.com/?size=100&id=g9mmSxx3SwAI&format=png&color=000000)

 ## Features

- Graphical User Interface (GUI) : The project comes with a user-friendly GUI that enables users to interact with the sorting algorithms visually.

- Sorting Algorithms : The visualizer supports a variety of sorting algorithms, including but not limited to:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort

- Real-Time Visualization : Users can observe the sorting algorithms in real-time, as the visualizer animates the sorting process step by step.

- Adjustable Speed & Array size : The visualizer allows users to control the speed of the sorting animation, enabling them to slow down or speed up the visualization as per their preference.

## Getting Started

Follow the steps below to get the Sorting Visualizer project up and running:

1. **Clone the Repository**: Clone this GitHub repository to your local machine using the following command:

   ```
   git clone https://github.com/ArrowCod/Sorting-Algorithm-Visualizer.git
   ```

2. **Open the Project**: Use an Integrated Development Environment (IDE) that supports Java to open the project.

3. **Run the Application**: Locate the main index.html file and run the application. This will launch the Sorting Visualizer GUI.

## Contribution

Contributions to this project are welcome and encouraged. If you want to contribute to the Sorting Visualizer, and also criticis, new idea, any updation always welcome, Discussions section is open for it.  follow these steps:

1. Fork the repository on GitHub.

2. Create a new branch with a descriptive name for your feature or bug fix.

3. Make your changes and improvements to the code.

4. Test your changes thoroughly.

5. Create a pull request to merge your changes into the main repository.

## Sorting Demo

1. **Bubble Sort** : 

Bubble sort is a simple comparison-based sorting algorithm that works by repeatedly stepping through a list, comparing adjacent elements, and swapping them if they are in the wrong order. The process is repeated until the list is sorted.

How It Works:
```
- Start at the beginning of the list.
- Compare the first item with the next one.
    - If the first item is bigger, swap them so the smaller one comes first.
- Move to the next pair of items and repeat the comparison and swap if needed.
- Keep doing this until you reach the end of the list. After one full pass, the biggest item will be at the end of the list.
- Go back to the start and repeat the process, but this time ignore the last item (since it's already in its correct spot).
- Continue until no more swaps are needed, meaning the list is sorted.
```

Time & Space Complexity:
``` java
Best-case: O(n) when the list is already sorted.
Worst-case and Average-case: O(n²)

Space Complexity: O(1)
```

https://github.com/user-attachments/assets/ec23dd1b-9237-4afc-9cc8-de4ca6fd4d92




2. **Insertion Sort**: 

Insertion sort is a simple and intuitive way to sort a list, similar to how you might sort playing cards in your hand. Insertion sort builds the sorted list one item at a time. It’s efficient for small lists or lists that are already mostly sorted but can be slow for large, unsorted lists.

How It Works:
```
- Start with the second item in the list (since the first one is already "sorted" by itself).
- Compare this item to the ones before it.
    = If it's smaller, move it left until you find the correct spot where it's larger than the item before it but smaller than the item after it.
- Insert the item in its correct position.
- Move to the next item in the list and repeat the process.
- Continue until you've gone through the entire list.
```


Time & Space Complexity: 
```java
Best Case: O(n)
Average and Worst Case: O(n²)

Space Complexity: O(1)
```

https://github.com/user-attachments/assets/f1634aa6-3097-4640-afa5-ddc105a9d3c7




3. **Merge Sort**:

Merge sort is an efficient, comparison-based sorting algorithm that uses the divide-and-conquer approach. It divides the list into smaller sublists, sorts them, and then merges them back together to form a sorted list. Merge sort is efficient with a consistent time complexity of O(n log n). It’s stable (maintains the order of equal elements) and works well with large datasets. However, it requires additional memory for the temporary sublists during merging.

How Merge Sort Works:
```
Divide:

  - Split the list into two roughly equal halves.
  - Recursively repeat this process until each sublist contains only one element (since a single element is already sorted).

Conquer:

  - Merge the sublists back together in sorted order.
  - To merge, compare the elements from each sublist and arrange them in order, creating a new sorted list.

Repeat:

  - Continue merging until all the sublists have been merged back into one sorted list.
```

Example:



Time & Space Complexity:
```java
Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n log n)

Space Complexity: O(n) due to the additional space required for merging.
```


https://github.com/user-attachments/assets/1293843e-b240-41e0-9bc1-683dd7c4a025




4. **Quick Sort**:

Quick sort is a highly efficient, comparison-based sorting algorithm that also uses the divide-and-conquer approach. It's known for its speed in practical applications and is one of the most commonly used sorting algorithms. Quick Sort is fast and efficient, especially for large datasets. It’s generally faster than other O(n log n) algorithms like merge sort because it sorts in place and has good cache performance. However, in the worst case (which is rare with good pivot selection strategies), it can degrade to O(n²) time complexity.

How Quick Sort Works:
```
Choose a Pivot:

  - Select an element from the list to be the "pivot." The pivot can be any element, but commonly it’s the last element,the first element, or a randomly chosen one.

Partitioning:

  - Reorder the list so that all elements less than the pivot come before it and all elements greater than the pivot come after it. The pivot will be in its correct final position after this step.

Recursively Apply:

  - Apply the same process recursively to the sublists formed by the elements before and after the pivot.

Combine:

  - Since the sublists are sorted in place, no further combining is necessary. The entire list becomes sorted as the recursion unwinds.
```

Example:

Time & Space Complexity:
```java
Best Case: O(n log n) Occurs when the pivot divides the list into two nearly equal parts.
Average Case: O(n log n) On average, the pivot will divide the list reasonably well, leading to efficient sorting. 
Worst Case: O(n²) Occurs when the pivot is the smallest or largest element, leading to highly unbalanced partitions (e.g., when the list is already sorted).

Space Complexity: O(log n) for the stack space used during recursion (for an in-place sort).
```

https://github.com/user-attachments/assets/04097e75-647f-4e79-8a01-76335a5a49d4




5. **Selection Sort**: 

Selection sort is a simple comparison-based sorting algorithm. It works by repeatedly finding the smallest (or largest, depending on sorting order) element from the unsorted part of the list and swapping it with the first unsorted element. It’s not the most efficient sorting algorithm, especially for large lists, due to its O(n²) time complexity. It’s useful when memory space is limited, as it only requires a constant amount of additional memory.

How Selection Sort Works:
```
- Start with the entire list.
- Find the smallest element in the unsorted portion of the list.
- Swap the smallest element with the first unsorted element.
- Move the boundary between the sorted and unsorted parts of the list one step to the right.
- Repeat the process for the remaining unsorted portion until the whole list is sorted.
```
Example:

Time & Space Complexity: 
```java
Best Case: O(n²)
Average Case: O(n²)
Worst Case: O(n²)

Space Complexity: O(1) because it sorts the list in place.
```

https://github.com/user-attachments/assets/16c61705-ef3f-4f9f-8bce-e4d852845a5c


## Acknowledgments

We would like to thank all the contributors and open-source projects that made this Sorting Visualizer possible. Your dedication and effort are greatly appreciated.

Special thanks to [Daniel Shiffman](https://youtu.be/67k3I2GxTH8?si=yAY-LQgcE47QRcg3) for motivate and inspired me to build this project.

Happy Sorting!
