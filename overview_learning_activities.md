# (Embarrassingly) Parallel Python - Overview and Learning Activities

Aitor, Zbigniew

## Learning activities

In the course of the lecture, a student will:  
 * Understand the difference between a thread and a process, and why using multithreading with Python is often not beneficial [Aitor]
    * Example exercise: We explain the basics of the GIL, then ask the students to hypothesize in pairs why (a) multithreading in python doesn’t really work and (b) why numpy magically works [10 mins, including discussion]
 ------- (~40 mins) -------
 * Identify which sorts of computational problems are better solved with multithreading vs. multiprocessing [Zbysek]
    * Example exercise (Kahoot): We list different sorts of problems, they need to figure out whether it is better suited to multithreading or multiprocessing (or neither) [~15 mins, including discussion]
 ------- (~1h) -------
 * Apply the multiprocessing module to an embarrassingly parallel problem and analyse the resulting speed-up [Aitor]
    * Exercise: Take our code and improve it, please :) [30 mins, Exercise 1 after the break, including discussion]
 ------- (~2h) -------
* Analyse the effect of threading on numpy execution and, from that, hypothesize the architecture of the laptop [Zbyszek]
    * Example plotting speed versus threads [30 mins, including discussion]
 * Examine the interaction between multiprocessing and numpy’s multithreading [Zbyszek]
    * Exercise: using multiprocessing, start 4 jobs with numpy and then see how many threads you spin up and how your speed-up DIES [20 mins, including discussion]
 ------- (~2h45) -------
 * Hear about related packages for parallel computing [Aitor]
