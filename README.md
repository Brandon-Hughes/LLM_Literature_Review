# CPSC 354 - Programming Languages
## Brandon Hughes 
## Language Interoperability

### Overall Question
How are programming langauges compatabile with on another and how are we able to improve it in the future?

**Introduction**

Language interoperability refers to the ability of different programming lanauges to work together within a systme or application. Since many applications that we use on a day-to-day basis incorporate many different programming languages to sastify an overall experience to their users, we are able to see the basis behind how langauges can be used with one another. An basic example of this can be seen behind HTML, CSS, and Javascript as they are used together quite often to create webpages. 

There are a couple of main points when it comes to making a language interoperable with another. One being the standardized data format they are using, such as JSON, XML, or Protocol Buffers will allow the different langauges to exchange easily and understand each other's data strcutres. Another is the APIs and and commmunication protocols will define how differenet systems or components can interact within itself and with other languages. Well-designed APIs can make it easier for different langauges to communciate and work together. Lastly, clear documentation and common conventions help ensure that different langauges components can work together smoothy. This inclues specifying how data should be formatted and how functions are abled to be called. By addressing these points as well as some additional ones, such as error handling and exception management, data types, and common runtime environment, lanaguages can be configured and even designed to interact effectively with another langauge, making it easier to build complex systmes up that would benefit from multiple langauges.

Language interoperability facilites the creation of robust, flexible, and maintainble systmes by enabling different components to work together harmoniously, regardless of the programming languages used. When creating interoperable languages you are able to integrate legacy systems or libraries written in older languages. Many legacy langauges such as C, COBOL, and PERL are not used within programming many of the applications that are made in this current time period. However by using interoperability, we were able to create langauges such as C++, Java, and Python that would be able to be interoperable with those legacy programming langauges and be able to use those functions and information that were already collected. 

**Notable Figures**

Some key individuals who have had the most significant impact on programming language interoperability would be James Gosling, Martin Odersky, and Anders Hejlsberg. 

* Which being the creator of Java, James Gosling's work on the Java Virtual Machine (JVM) was foundational in enabling langauge interoperability. The JVM supports a very wide ranage of lanaugages beyond Java, such as Kotlin and Scala, which laid down many foundations for how multiple langauges would be able to operate within a single runtime environment. 

* Anders Hejlsberg is the lead architect of C# and a key figure behind developing the .NET framework. The .NET Common Language Runtime (CLR) allowed for interoperability between multiple legacy lanauges with in the ecosystem. Instead of a single runtime environment, he was able to create a unified enivornment where different langauges could coexist and interact with one another. 

* Barbara Liskov was an important part of creating the idea behind object-oriented programming. Her research on type systems and software design principles helped to influence how lanaguages would handle inheritance, polymorphism, and type safety, which are essential for ensuring compatibility between different programming langauges.

**Challenges**

While, as seen above, language interoperability is very beneficial towards solving many problems within the programming community, it does have its own set of challenges to mapping languages to one another.

Some big challenges include:
1. Data Conversion and Mapping: 
    Within in different languages they may have similar data types, structures, and convetions but often they use it a little bit differently. Converting data between langauges can end up becoming complex and create many errors.
    To solve this issue, many langauges output to a standardized data format to allow for simplicity. An example of this being python and java both being able to output as a json file or even an XML.

2. Debugging and Error Handling:
    Debugging issues in a system with multiple langauges can be difficult, as errors might generate across language boundries and show up in unpredictable ways. 
    To solve this issue, when debugging implmeent comprehensive logging and monitoring to trace the errors created and when they are actually being generated.

3. Maintenance: 
    When handling a system with multiple languages, maintaining it can be more complex than working with a single language, which can ultimately require more specialized knowledge and coordination within the different langauges. When you are updating certain programming languages, they may end up even losing certain dependencies or lead to version conflicts.
    To solve this issue, having an overall team that collaborates with eachother constantly to monitor each individual version of the programming langauges and changes made to it will ultimately bring about better control of the system. 

**Future Goals**

In the future, interoperability is going to become an important part of how we write code so that not only we an use it but if we want to write it on similar applications such as Objective-C/SwiftUI for IOS or Kotlin/Java for Androird it will become much easier. To improve on interoperability, we can either solve the challenges that are given to us through easier solutions or propose different ideas and standardized formats so that it becomes much easier. Many improvements usch as promoting open standards, general interoperability libraries, and unified development environments will allow for better tools to combine langauges together. 

Some usages for the interoperability in the future, is in collaboration with artificial intelligence which has seen a rise in a few previous years. Being able to use artificial intelligence to be able to solve the issues between programming langauges or being able to transfer from one language to another is an idea that can be proposed in the future where you enter the program in one language and it can ouptut it an another language. Another usage is being able to standardized data collection through processing, sharing, and replication to increase the significance of results obtained through aritifical intellegence.<sup>[2](https://www.researchgate.net/profile/Adam-Graefe/publication/383335311_How_Interoperability_Can_Enable_Artificial_Intelligence_in_Clinical_Applications/links/66cde0ee64f7bf7b1944c168/How-Interoperability-Can-Enable-Artificial-Intelligence-in-Clinical-Applications.pdf)</sup>



**Questions**
1. What is Language Interoperability?
2. What are the main points of a language to make it interoperable?
3. What are some challenges that come with langauge interoperabiliity?
4. How can language interoperability be improved for average users of multiple languages?

**References**

1. [Popularity, Interoperability, and Impact of Programming Languages in 100,000 Open Source Projects](https://ieeexplore.ieee.org/abstract/document/6649842)

2. [How Interoperability Can Enable Artificial Intelligence in Clinical Applications](https://www.researchgate.net/profile/Adam-Graefe/publication/383335311_How_Interoperability_Can_Enable_Artificial_Intelligence_in_Clinical_Applications/links/66cde0ee64f7bf7b1944c168/How-Interoperability-Can-Enable-Artificial-Intelligence-in-Clinical-Applications.pdf)

3. [Programming Language Interoperability in Distributed Computing Environments](https://link.springer.com/chapter/10.1007/978-0-387-35565-8_24)



**LLM**

The large-languge model that I decided to use for this project is going to be ChatGBT GBT-4o.

