1. when i issue mvn install what all things happen in background?
2. what are the settings you need to do before running mvn deploy?
3. why maven takes much time for 1st execution and from 2nd execution it will take less time?
4. what is multi module project in maven and what are the setting you want to do in multi module parent and child project? what is dependency management?
5. what is transitive dependency?
6. .m2 is local repository for maven, now I don’t want to use .m2 folder as my local repository I want to use some other folder as my local, is it possible in maven? If yes, how would you do that?
mvn install -Dmaven.repo.local=/alternate/repo/location 
7. maven follows convention over configuration that means it assumes code should be there under src/main/java, test cases under src/tests and many more.Here my requirement is I don’t want to follow that conventions I need to use different folder structure is that possible in maven?
mvn help:effective-pom -Doutput=pom_eff.xml
8. What are dependency and plugin in maven? Give one example for each?
9. What are 3 build life cycles in maven?
10. In Which tag we will mention output artifact type( like jar, war or any other)?
11. What are things you need to set, if you want download dependency from private repository ?
12. What are the issues you faced while working on maven projects?
13. Command to skip the test cases in maven
14. what is multi module project?
15. what is the importance of dependency managment?
16. what are the settings that you need to do for mvn deploy ( to push artifcats to repository )?
17. mvn version that you have used?
18. Tell me 3 build lifecycle in maven? What does mvn site does?
19. Is there way by which we can set local repository as some other custom directory, other than .m2?
20. Settings that you make for mvn deploy?
21. What is the default value of packaging tag? What other values for other artifact types?
22. What are GAV's?
23. what are the tags that you came across in pom.xml?
24. Explain maven life cycle