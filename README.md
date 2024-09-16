# CPSC 354 - Programming Languages
## Brandon Hughes 
## Language Interoperability

### Overall Question
How are programming languages compatible with one another and how are we able to improve it in the future?

**Introduction**

Language interoperability refers to the ability of different programming languages to work together within a system or application.<sup>[1](https://digitalcommons.morris.umn.edu/horizons/vol1/iss2/3/#:~:text=Interoperability%20of%20programming%20languages%20is,between%20potentially%20very%20different%20languages.)</sup> Since many applications that we use on a day-to-day basis incorporate many different programming languages to satisfy an overall experience to their users, we are able to see the basis behind how languages can be used with one another. A basic example of this can be seen behind HTML, CSS, and JavaScript as they are used together quite often to create webpages. 

There are a couple of main points when it comes to making a language interoperable with another. One being the standardized data format they are using, such as JSON, XML, or Protocol Buffers will allow the different languages to exchange easily and understand each other's data structures. Another is the APIs and communication protocols will define how different systems or components can interact within itself and with other languages. Well-designed APIs can make it easier for different languages to communicate and work together. Lastly, clear documentation and common conventions help ensure that different languages components can work together smoothy. This includes specifying how data should be formatted and how functions are able to be called. By addressing these points as well as some additional ones, such as error handling and exception management, data types, and common runtime environment, languages can be configured and even designed to interact effectively with another language, making it easier to build complex systems up that would benefit from multiple languages.

Language interoperability facilities the creation of robust, flexible, and maintainable systems by enabling different components to work together harmoniously, regardless of the programming languages used. When creating interoperable languages, you can integrate legacy systems or libraries written in older languages. Many legacy languages such as C, COBOL, and PERL are not used within programming many of the applications that are made in this current time. However, by using interoperability, we were able to create languages such as C++, Java, and Python that would be able to be interoperable with those legacy programming languages and be able to use those functions and information that were already collected. 

**Notable Figures**

Some key individuals who have had the most significant impact on programming language interoperability would be James Gosling, Martin Odersky, and Anders Hejlsberg. 

* Which being the creator of Java, James Gosling's work on the Java Virtual Machine (JVM) was foundational in enabling language interoperability. The JVM supports a very wide range of languages beyond Java, such as Kotlin and Scala, which laid down many foundations for how multiple languages would be able to operate within a single runtime environment. 

* Anders Hejlsberg is the lead architect of C# and a key figure behind developing the .NET framework. The .NET Common Language Runtime (CLR) allowed for interoperability between multiple legacy languages within the ecosystem. Instead of a single runtime environment, he was able to create a unified environment where different languages could coexist and interact with one another. 

* Barbara Liskov was an important part of creating the idea behind object-oriented programming. Her research on type systems and software design principles helped to influence how languages would handle inheritance, polymorphism, and type safety, which are essential for ensuring compatibility between different programming languages.

**Challenges**

While, as seen above, language interoperability is very beneficial towards solving many problems within the programming community, it does have its own set of challenges to mapping languages to one another.

Some big challenges include:
1. Data Conversion and Mapping: 
    Within in different languages they may have similar data types, structures, and conventions but often they use it a little bit differently. Converting data between languages can end up becoming complex and create many errors.
    To solve this issue, many languages output to a standardized data format to allow for simplicity. An example of this being python and java both being able to output as a Json file or even an XML.

2. Debugging and Error Handling:
    Debugging issues in a system with multiple languages can be difficult, as errors might generate across language boundaries and show up in unpredictable ways. 
    To solve this issue, when debugging implement comprehensive logging and monitoring to trace the errors created and when they are being generated.

3. Maintenance: 
    When handling a system with multiple languages, maintaining it can be more complex than working with a single language, which can ultimately require more specialized knowledge and coordination within the different languages. When you are updating certain programming languages, they may end up even losing certain dependencies or lead to version conflicts.
    To solve this issue, having an overall team that collaborates with each other constantly to monitor each individual version of the programming languages and changes made to it will ultimately bring about better control of the system. 

**Future Goals**

In the future, interoperability is going to become an important part of how we write code so that not only we can use it but if we want to write it on similar applications such as Objective-C/Swift UI for IOS or Kotlin/Java for Android it will become much easier. To improve on interoperability, we can either solve the challenges that are given to us through easier solutions or propose different ideas and standardized formats so that it becomes much easier. Many improvements such as promoting open standards, general interoperability libraries, and unified development environments will allow for better tools to combine languages together. 

Some usages for the interoperability in the future, is in collaboration with artificial intelligence which has seen a rise in a few previous years. Being able to use artificial intelligence to be able to solve the issues between programming languages or being able to transfer from one language to another is an idea that can be proposed in the future where you enter the program in one language, and it can output to another language. Another usage is being able to standardize data collection through processing, sharing, and replication to increase the significance of results obtained through artificial intellegence.<sup>[3](https://www.researchgate.net/profile/Adam-Graefe/publication/383335311_How_Interoperability_Can_Enable_Artificial_Intelligence_in_Clinical_Applications/links/66cde0ee64f7bf7b1944c168/How-Interoperability-Can-Enable-Artificial-Intelligence-in-Clinical-Applications.pdf)</sup>

**References**

1. [Interoperability in Programming Languages](https://digitalcommons.morris.umn.edu/horizons/vol1/iss2/3/#:~:text=Interoperability%20of%20programming%20languages%20is,between%20potentially%20very%20different%20languages.)

2. [Popularity, Interoperability, and Impact of Programming Languages in 100,000 Open Source Projects](https://ieeexplore.ieee.org/abstract/document/6649842)

3. [How Interoperability Can Enable Artificial Intelligence in Clinical Applications](https://www.researchgate.net/profile/Adam-Graefe/publication/383335311_How_Interoperability_Can_Enable_Artificial_Intelligence_in_Clinical_Applications/links/66cde0ee64f7bf7b1944c168/How-Interoperability-Can-Enable-Artificial-Intelligence-in-Clinical-Applications.pdf)

4. [Programming Language Interoperability in Distributed Computing Environments](https://link.springer.com/chapter/10.1007/978-0-387-35565-8_24)

**LLM and Questions**

The large-language model that I decided to use for this project is going to be ChatGPT GBT-4o.
1. What is Language Interoperability?
2. What are the main points of a language to make it interoperable?
3. What are some challenges that come with language interoperability?
4. How can language interoperability be improved for average users of multiple languages?

