Lesson 2: What is a real world problem?
=============================

One of the biggest problems that most people face when they are trying
to progress in towards a goal is finding problems to solve. Working
through a textbook or a course where there are problems laid out for
you. Having the problem presented in such a way removes a great deal of
the thought required because in the real world, problems aren’t
generally so simple to find. For example, when you are getting your
education everything is laid out for you in the form of a curriculum.
You have a certain amount of courses that you have to pass and the grade
which you need is also decided by the administration. There is not
thinking involved in deciding for yourself what is an acceptable grade
to get to pass the subject, but rather you just have to focus on
learning the material in the class and pad the tests. This eliminates a
lot of the thought processes that you need and makes questions such as
“why” unnecessary. If you asked why do you need a certain grade to pass,
then the answer will most likely be that it’s set by the education
ministry. A situation like this is similar to a “sandbox” in the
development world. This is used to refer to an environment that isn’t
real, but functions like a real environment in which there are certain
constraints on what can be done.

There are very logical reasons why education is structured like this, so
this is in no means a disparagement on the educational system. However,
what tends to happen is that when you need to make decisions where the
problem isn’t laid out clearly then it’s difficult to know where to
start. Which is exactly what is expected if you haven’t been trained in
it. For example, if we look at education versus the job market, there is
a stark difference in how the two need to be approached. When you have
finished your education - whether it’s high school or university - you
need to find a job. There is not formula to find a job that is
comparable to the formula used to get people educated. You can pass a
certain number of courses after which you get a degree at university for
example, but you cannot go the a certain amount of job workshops then
automatically get a job. The job market doesn’t work like that. Instead
what it does is show you how the market works in the real world. From
that you have to do some investigative work to find out where you can
get an opportunity. This is an important difference between the job
market and educational system because you have to decide where you start
and what “grade” is acceptable.

It is, therefore, important to learn to prioritize what is the most
urgent problem and solve that first. In the job market example, your
first priority is to get a job because you either get a job or you are
jobless. The first option is good and the second option is bad. Contrast
that to deciding between two jobs that you could get. In that case, both
options are good, so while there is still a choice that needs to be
made, it’s different from choosing between being jobless and having a
job. The same applies to other decisions in life and especially the
decisions in programming.

Decisions in programming
------------------------

Up until now, we haven’t discussed anything directly related to writing a program. 
This has been intentional because the exercise in
this section is going to address that. Programming is actually better
described as problem solving and using the four components of
computational thinking is a guide on how to do that. So, you actually
have been learning to program - although you need to learn the
practicalities of it now. Programming languages are simply ways in which
you can communicate the plan you have designed to a computer. The
computer then does the work and what appears on the screen are the
results. This could be what you expected or it could be unexpected. Base
on what appears on the screen, you can continue with your plan or adjust
mistakes. You repeat this process until the main problem is solved. We
are going to learning to program in Python, but the programming language
is largely irrelevant because writing code is similar to writing a book.
There are two components that are important to writing a book: the
structure and the language. The structure is the way in which the book’s
narrative flows and the language is the what words that are written on
the pages. In the same way, computational thinking is the structure of
the program (the logical flow) and the programming language (the
characters on the screen) are what brings that structure to life. They
are both necessary and there can be errors in both, so it’s important to
understand how they work together.

What is an error?
-----------------

The way in which programming languages work vary depending on the
language, but all programming languages produce error messages when
something has gone wrong. A lot of new programmers get intimidated with
error messages because it may seem like they have failed in writing
their code. The error messages usually seem intimidating with a bunch of
text on a red background, but getting an error message isn’t a failure.
It simple means there is a mistake in your program and the error message
is giving you a log of where it could be. Usually the last line of the
error message is where the immediate problem is that’s preventing the
program from running. Learning to understand what these error messages
mean takes some time, so don’t worry if it seems overwhelming at first.
In 90% of cases, you can enter the last line of the error message in a
search engine such as `Google <https://google.com>`__ or a website such
as `Stackoverflow <https://stackoverflow.com/>`__ and there should be an
answer similar to the one you are looking for.

There are many different kinds of error messages, but for the sake of
simplicity we can divide them into two categories: errors which stop the
program from running and logical errors. When you have written some code
that violates the syntax of the language then your program will not run
until you fix the problem. To use an analogy to explain this, image you
write a Tweet, but before the Tweet gets published it checks if your
spelling and grammar is correct. If it’s not correct then it shows an
error message with the line where the spelling or grammar error is
located. You have to correct the mistake and resend the Tweet. That is
similar to how programming works in that error messages are just showing
you where a mistake is and once you fix it then you can proceed.

On the other hand, a logical error is one in which your program runs,
but it’s not doing what you expect it to do. If we go back to the Tweet
example, in the case of a logical error, the Tweet gets send without any
errors, but the actual writing doesn’t mean what you intended it to
mean. This type of error is the most difficult to find because it
doesn’t stop the program from running, so you have to understand why the
program is not doing what you intended. When you find the error it could
be some big mistake, but usually it’s the smaller mistake that are more
difficult to find. For example, if you are trying to calculate the
average of two numbers, but instead of the correct answer you get a much
larger number. You later find out that you multiplied (*) the two
numbers together instead of adding (+) them together. These kinds of
errors are very common and just like any other problems in life their
causes are usually quite straightforward: you were distracted and didn’t
notice the error, you were tired and didn’t focus when you wrote the
code;, you were nervous to make a mistake, so you made a mistake, etc.

The best way to deal with errors that you can’t seem to fix is to take a
break from the code and do something else. Come back to the code at a
later time and look through it with fresh eyes. Often you will notice
things that you didn’t notice before and this could help you to solve
the problem much easier. The main takeaway from error messages is that
you mustn’t be overwhelmed by them, they are there to help you find the
error and they don’t indicate you have failed.

Exercise 1
----------

The first exercise you are going to actually program without knowing how
to program. Sounds impossible, right? Well, it’s possible if you
understood the previous lessons. Just like in the real world, the task
is not going to be laid out perfectly, but rather you have to decide
what is the best way to do it. In programming languages, it’s customary
for the first program to print the words “Hello world!”, so to keep with
custom, you task to print “Hello world!” to the screen using the Python
programming language. You can do this however you want, but the
following are a few tips 1) Think about Occam’s Razor (the simplest
solution is usually the optimal one) 2) Don’t ask anyone for help - if
you get frustrated then take a break and walk around. The point is for
you to solve the problem, not someone else. 3) If you have tried
absolutely everything and you can’t figure out the answer, then read
exercise hint 1.

.. dropdown:: Exercise 1 hint 1

   The most difficult step in solving a problem is knowing where to start.
   When you have no idea what to do, the problem may seem overwhelming, but
   if you don’t know what to do then the best place to look for answers is
   from what other people have done. Since we have the internet and the
   world is becoming more and more connected, there are many different ways
   to find out how other people have solved the problem or similar
   problems. You can use those as starting points to solve your problem. A
   good rule of thumb to help with this is asking yourself what, why, how
   and where. - **What** am I doing? - Looking for a way to print “Hello
   world!” to the screen - **Why** am I doing this? - As a way to
   understand how to solve problems that I don’t have concrete instructions
   for. - **How** am I going to do this? - I don’t know yet, I need to use
   the Python programming language - which I don’t know - but that provides
   some context. - These keywords phrases “printing in the Python
   programming language” or “how to print hello world in the Python
   programming language” are good starting points. - **Where** am I going
   to do this? - I need to find somewhere to write the code, so key phrases
   such as “where can I write Python programming code” could be useful.

   Using these clues, you can try find some more concrete answers. Of
   course, the phrases are just to get you to understand the basic through
   process and you can use whatever means to get the task done. The
   fundamental principles are always keep it as simple as possible.
   Especially for these exercises, the answers are should be very simple,
   so if you find something that looks extremely complicated then try look
   for something simpler. You can even search on YouTube for videos
   explaining these concepts because there are great resources published on
   YouTube for people learning to write code. One last point is that you
   don’t have to feel overwhelmed by this. If you are getting nowhere and
   feeling frustrated then take a break and come back to the problem later.
   If you are still not finding a solution then move on the exercise hint 2.

.. dropdown:: Exercise 1 hint 2

   Read the exercise hint 2 fully before trying anything. In order to write
   Python code, you need to install Python on your local machine, create a
   ``.py`` file which contains the code you want to run and execute the
   code via the command line (or terminal). For example, you can create a
   file called ``hello_world.py`` and run it from the command line using
   the following command ``python hello_world.py``. There are a few steps
   in this process, but each step could have several problems. For example,
   it won’t work if you don’t have Python installed on your computer. If
   the ``hello_world.py`` file is not in the correct directory then it also
   won’t work. If you haven’t written the commands correctly in the file,
   then it won’t run properly. If you haven’t got the right version of
   Python then you might have to use ``python3 hello_world.py``, so
   ``python hello_world.py`` won’t work in this case. You might not even
   know what a command line is, so this simple task can seem overwhelming
   again even if you’ve done all the preparation as laid out in the
   previous lessons.

   Well then what can we do if even the most simple exercise is so
   complicated? We take a look at the original question which is:

      Print “Hello world!” to the screen using the Python programming
      language.

   In the the exercise there is no mention of installing anything on your
   local machine and there are no requirements for setting up any
   environment for writing Python code. So, since we have access to the
   internet, we could look for ways in which to write Python code without
   the need for setting anything up. In recent times, there have been a lot
   of websites that have been created to help people who are coding or
   learning to code. Since it’s difficult to understand what a piece of
   code is doing without seeing the results, many developers have used the
   latest technologies to create coding environment within browsers. This
   means that they can write Python (or other programming languages too) on
   designated sections of their websites then press a button and the code
   executes (in other words, the program runs). This makes it easier for
   people to share code and show other developers the problems they are
   facing, since they can run the code themselves in their browsers without
   the need to set everything up.

   Of course, the complexity of these environment differs from website to
   website, but usually the basic functionality works well. So, the easiest
   way to solve the current exercise is to look for online Python editors.
   This eliminates the need to install anything on your local machine and
   it also eliminates errors that could be caused from different operating
   systems (Window, Linux or MacOS). If you have made it to this point and
   you still cannot solve the problem then take a break, do something else
   and come back to it with some fresh eyes. If you are still have trouble
   after that, then go on the exercise hint 3 where I will provide a
   solution to this problem.

.. dropdown:: Exercise 1 hint 3 (solution)

   The easiest way to do this exercise is to simply search “online Python
   editor” on Google and the first few results will show you such an
   editor. Here are the websites that I got when I searched this phrase
   `Programiz <https://www.programiz.com/python-programming/online-compiler/>`__,
   `Online Python <https://www.online-python.com/>`__ and
   `OnlineGDB <https://www.onlinegdb.com/online_python_compiler>`__. All of
   these websites allow you to write Python code and execute the code by
   pressing the run button. There you have it, you’ve just written some
   Python code.

   Now that you have it running, you can play around with the code. It’s
   always good to experiment with what’s going on because I could explain
   to you every detail, but it might not make sense to everyone. When you
   are working with the code yourself, you can experiment with changing the
   code and observe how the results change. So a few things you could try
   is remove some elements of the code and see what happens. Replace the
   quotation marks (“) with apostrophes (’), does the code still run? More
   importantly is it still giving the expected output? What happens when
   you remove the last close round bracket ())? Does the code still run or
   does it give an error? Can you replace the round brackets () with square
   brackets []? If you get an error doing this then can you draw the
   conclusion that for a print statement you can use round brackets and not
   square brackets? One final experiment you can try is deleting everything
   from the window and retyping it from memory. Can you get it running
   again or does it give an error? If it gives you can error, can you
   understand the error message?

   You don’t have to answer the questions above or you can try other
   experiments. The point is to get it working then break it then fix
   again. This is all to make you think about what’s happening and what the
   results are if you change the code in a certain way. That being said, if
   the process can be so simple, then you might be wondering what’s the
   point of setting up a Python environment on your own computer? For
   starters, if you don’t have access to the internet then you can’t run
   anything online. However, more important than that, the online Python
   editors are usually very basic and don’t include more advanced packages
   and libraries that you might need. So, when you are working on
   developing programs for specific tasks, you will need to setup
   environments of your own, but remember to keep it simple. If all you
   need to do is print a simple sentence then the online editors are
   sufficient. A big component of programming (and problem solving in
   general) is to get the best results, with the least effort in the most
   efficient way possible. As was discussed previously, though, you won’t
   always achieve this because of time, lack of knowledge or other
   constraints. So, don’t worry about that for now, but rather focus on
   getting it working and keeping it simple.


