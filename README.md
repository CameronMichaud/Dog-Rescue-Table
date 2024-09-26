# CS340-Client-Server-Development
<h2>Video Demonstration</h2>

[![Dashboard Demonstration](https://img.youtube.com/vi/wNS2JfujClQ/0.jpg)](https://www.youtube.com/watch?v=wNS2JfujClQ)

___

How do you write programs that are maintainable, readable, and adaptable?
- I try to write programs by simplifying and modularizing code whenever it would be beneficial to write a dedicated function/struct/variable rather than hard-coding. This method is useful as any change that's needed for a specific process can be altered at the source rather than a by-instance approach. It makes the code itself much easier to read and understand and adapt to fit future constraints placed upon the codebase in the future.
___
How do you approach a problem as a computer scientist? How did this project differ to prior ones from other classes/assignments?
- I approach developing a program in modules (often commenting large headers to better define sections of a codebase for myself), so when I encounter an issue such as one I had for this project with sending an update argument to a read function for MongoDB, I will attempt to reproduce the problem in a separate environment if possible (and worth the time it would take to recreate), or I will develop a unique function to test to problem so as to not produce a solution to the harm of the rest of the codebase. For instance I could rewrite the original read function in my Python module (which would most likely cause other issues with different functions) or rewrite the logic for sending the argument (attempting to create and operate on a separate data type to try and manipulate the data to be accepted by the function) which can often produce disorganized/convoluted code. But instead I develop in a separate function so that I can attempt at the current logic of the read function, and not create wasted time trying to repair the code where the issue arose in the original code. I can develop a solution in an isolated environment simply place the solution back to where it's needed and clear the testing environment.
- I at first did not use this approach in my first two years in my CS program, but notably during a Computer Graphics and Visualization class that had us develop a 3D scene in OpenGL, I encountered this issue quite a lot which led to unintended errors by creating a very unorganized and unelegant solutions to problems I encountered. By the end of that class I had an entire separate environment where I could copy specific sections of code that I wanted to optimize or modularize.
___
What do computer scientists do, and why does it matter? How does your work help a company like Grazioso Salvare to do their work better?
- I think that computer scientists are important to companies like Grazioso Salvare because computer scientists develop ways to make operations more efficient. For a software engineer for example, you work to make your own work more efficient to be able to develop faster and create better code. The work you produce though is to make the operations of whoever you develop for more efficient, or to provide abstractions of different processes. For Grazioso Salvare, the work I did could help them work better by identifying potential rescue animals for local animal shelters in a much quicker manner by having a digitized database that can be sorted to fit the constraints they're searching for. This makes the whole processing operation much more efficient as one simply needs to consult the database to find the potential rescue animal, then using the information present in the database, make a decision whether to train the animal for a given type of rescue. This is an abstraction of the work that this would normally take, as the database represents the work of contacting each individual shelter and collecting the information of each animal, including the then processing of the information gathered later into their own specific categorizations (such as the different rescue specialties categorized by this dashboard).