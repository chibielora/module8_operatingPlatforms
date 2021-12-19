# Module 8 - Operating Platforms

Module 8 from the course Operating Platforms with the instructor Kevin Belcher

- Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

    The parent company, The Gaming Room, presented to our company CTS their project for a new cooperative, multi-platform game. The name is Draw it or Lose it, and was based on a TV show from the eighties called Win, Lose, or Draw, in which two teams are formed to compete in a drawing game. A representative of each team is sent to the whiteboard to draw whatever word they picked in the beginning phase of each game. The team that gets most drawings right wins. The suggested prototype of the Draw it or Lose it game briefly changes the drawing board to a grid-based image rendering for each of the teams, cutting out the need for sockets to handle real-time whiteboarding.

- What did you do particularly well in developing this documentation?

    The part of the documents I enjoyed working the most was the Evaluation topic, which contained basic information of each of the operating systems we were planning to use during the development. I spent many days reading different sources and watching videos on compatibility to understand exactly how the foundation should be in order for the game to work.

- What about the process of working through a design document did you find helpful when developing the code?

    After the UML diagram we designed, there was an "official" diagram given in Project One. That UML was exactly what I needed to understand how the code should work. By knowing how my connections in the software would work, I could picture how my schemas were going to work on the server-side, in case we needed to build that part as well. That overtly clarified what I should have in the recommendations' topic.

- If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

    I would pick "Operating Systems Architecture" topic in the recommendations. I could not understand what the legend under it really wanted for a response; if it were application design architectures, server architectures, or platform architecture. Since we had a recommended reading about Operating Systems Architecture in module 1, I just resorted to studying strictly platforms. My instructor left observations after grading that clarified what I should have focused on instead.

- How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

    Expecting client's needs and implementation of features is crucial for software development. It helps you not only save money for the customer, but it saves you precious time. At first, I did not understand how the game looked like at all, so I went on YouTube to watch the old TV show. After that I understood why there should be only one instance of the game and also how the teams should be organized. I thought first that there could be an unlimited amount of groups playing one game, which proved to be false after I read the document and understood how the game worked. Had I not tried reading production documentation through the game's specter, I would have to go back to the **team** and **player** classes to rework in their functionality.

- How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

    My approach was to tackle questions individually about how each of the elements in the entire system worked. I started with the UML diagram giving me instructions on how the classes should be organized. Then, when I tried to understand why players were contained in teams and not the opposite way, I watched how the real-life game worked. That also helped me understand how the game was time-sensitive and needed fast image rendering. Then, I went to check if a hybrid platform would be better than a fully cloud-operated. Then, I realized I did not know how cloud storage and pointing to indices worked. Online tutorials were extremely helpful in providing me the content, but I needed to separate the important information from the interesting but unnecessary for the project. I want to understand better how S3 and sockets work and how to develop a project using exclusively cloud technology. I also want to learn about all the different options of cloud computing that can be implemented in games. Furthermore, I believe game projects are the best way to learn concepts well and to have fun with what you are creating at the same time.
