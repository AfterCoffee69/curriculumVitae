# Roman Moiseenko
![img](/image.jpg)<br>

### Contacts:
 - [VK](https://vk.com/after.coffee)
 - [Instagram](https://www.instagram.com/after.coffee69/)
 - [GitHub](https://github.com/AfterCoffee69)   
 - [Gmail](mailto:humidityisrising@gmail.com)

# About me
>I am a second-year computer science student.<br>
Now I'm studying programming to become a Full-stack developer.<br>
I have experience in web, desktop and game development.<br>
I'm so ambitious and responsible about my projects.

## Technologies stack 
 - C# **(fav)**
 - C++
 - Python
 - HTML/CSS
 - JS
 - SQL (SQLite, MS SQL Server)

## Languages
 - Russian
 - Belarussian
 - Ukranian
 - **English (B2)**

# Work Experience
>I tried my hand at different areas of development such as<br>
web development, desktop development and gamedev.<br>
Like everyone, I face difficulties in programming,<br>
but if I am passionate about a project, I dedicate all of myself time to it.<br>

## My projects
 - Desktop Calculator (C#/WindowsForms)
 - Calories Calculator (HTML/CSS/JS)
 - Desktop 2D Platformer (C#/Unity)

# Code example

C# Selection Sort
```C#
    static int[] SelectionSort(int[] array)
    {
        for (int i = 0; i < array.Length - 1; i++)
        {
            int min = i;
            for (int j = i + 1; j < array.Length; j++)
            {
                comparisonSelection += 1;
                if (array[j] < array[min])
                {
                    min = j;
                }
            }
            int temp = array[min];
            array[min] = array[i];
            array[i] = temp;
        }
        return array;
    }
```

C# Binary Tree Postorder Traversal
```C#
    public void PostorderTraversal()
    {
        if (leftNode != null)
            leftNode.PostorderTraversal();
        if (rightNode != null)
            rightNode.PostorderTraversal();
        Console.Write(data + " ");
    }
```
