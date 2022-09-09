---
layout: essay
type: essay
title: "Why Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2022-09-08
published: true
labels:
  - Software Engineering
---

## Roadblocks in Software Engineering

In the field of Software Engineering you will constantly be collaborating with other people, teams, and companies from around the globe. Designing programs and coding effectively requires a tremendous amount of knowledge and years of studying and many people will rely on you and your software to work. However, with the addition of a vast selection of programming languages, IDE’s, and operating systems (just to name a few), you are bound to run into an issue that requires an experienced user’s input. Trying to solve these issues on your own can be extremely tedious and you’ll often hit dead ends when trying to brute force your way through. This can halt entire business operations and software development which can be detrimental, especially if you’re in a position where other people are relying on your program to work. 

## What’s a smart question?

The use of open source has become extremely popular in the past decade and has proven to help thousands of individuals solve their specific problems. There are many communities and forums that are specifically tuned for a topic that people may have questions/issues about. These topics aren’t just about programming/software development but can extend to virtually anything, both trivial and non-trivial. Just to name a few, these topics can range from cars, computers, and cooking. The reason for all of these different topics is to provide a way, specifically for ‘newbies’, to learn from more experienced users/professionals within that respective field. However, you’ll often find ‘losers’ on these forums that ask questions in a ‘dumb’ way. I don’t mean that these ‘dumb’ questions are trivial, but the way they’re asked is what makes them dumb. What I mean by this is that people will often spit out their questions and expect people to give them a respectful and detailed answer. These kinds of people do not appreciate the process of learning and feel entitled to get free help on their issue. People need to learn how to ask ‘smart’ questions and show interest in whatever topic they’re discussing because it will result in more efficient answers. In Eric Raymond’s How to ask questions the smart way, Eric describes hackers as users that enjoy difficult problems and thought-provoking questions. These types of people enjoy solving issues and it acts as a stimulus to them as it can often reveal problems that they might have not noticed themselves. Hackers have a reputation for being hostile or arrogant, but what most people don’t know is that this type of behavior is mainly directed at people that ask not so smart questions. Learning to ask smart questions is essential because they can give you the best chance at solving your problems in the most efficient way, both in time and logic.

```
Please help stopping the form action



Check function not work !! Please help

  <php?
    function Check (){

      if ($_SERVER["REQUEST_METHOD"] == "POST") 
     {      
    if (!is_numeric($_POST["num1"])) 
    {
    $Err1 = "Num1 is not numeric"; 
    }
  if (!is_numeric($_POST["num2"])) 
  {
   $Err2 = "Num2 is not numeric"; 
  } 
  if ( $Err1 = $Err2 = ""){
  return true;}
  else  return false;
 }

return false;

}
 ?>
```

This question from Stack Overflow would be considered a not so smart question by Raymond’s standards. Let's start with the subject header: ‘Please help stopping the form action’. Using the words ‘please’ or ‘help’ in the subject header will portray you as a desperate individual that demands assistance. Most users and hackers don’t want to help someone that is rudely asking for assistance and these types of subject headers will more often than not result in mediocre answers or no response at all. As we dive deeper into the question, the user then says “Check function not work !! Please help”. This goes back to being rude and expecting people to help, just because you’re posting in Stack Overflow doesn’t mean that you are entitled to an answer and can be rude, please remember that you are using a free forum site with the goal of getting assistance with an issue. The rest of the post is pretty much source code, which is the one smart thing that this person did. Posting your code with your question is essential because it allows other users to look at exactly what you are trying to solve and will allow others to replicate/trace your issues. This user luckily got an answer from an individual but again we fail to see any sort of appreciation for the answer which directly goes back to rudeness.

```
Google Cloud SQL + Hikari CP + Communications link failure



I'm experiencing intermittent connectivity errors from a Spring Boot application communicating with a D1 Google CloudSQL Server with the configuration settings described here HikariCP MySQL settings

I was wondering if anyone has encountered this before.

I've read the FAQ posted here Hikari FAQ and I'm wondering if my default idleTimeout and maxLifeTime (30 mins) settings might be at fault; wait_timeout and interactive_timeout on the server are both set to default 28800s (8 hours).

The FAQ says that these two settings should be about a minute less that the server settings, but if I'm losing connections after 30 minutes I can't quite see how upping the maxLifeTime to 7hrs 59mins is going to improve the situation.

Does anyone have any recommendations?

```
 
This next question would be considered a smart question. Starting with the subject header: ‘Google Cloud SQL + Hikari CP + Communications link failure‘. Raymond addresses the subject header as one of the most important aspects of asking a question. This is what the public sees first about your question. It's important to use the ~50 characters of space you have wisely in order to portray your issue and entice people to help you. Raymond describes a useful convention for subject headers which is “object - deviation”. In our example, the “object” refers to ‘Google Cloud SQL + Hikari CP + Communications’ and the “deviation” refers to ‘link failure’. This is a good convention as it allows potential helpers to quickly gather information about what the general issue is and it’s straight to the point. Under this post, the user then goes deeper into what his issue is and provides links to his server settings. This is extremely helpful to hackers as it gives them the ability to reproduce the problem and allows them to know more about the issue at hand and the specific software/hardware components associated with it. The user then states that he’s read the FAQs but is still stumped. This is a key component when asking questions because it shows that you are spending the extra effort into trying to learn and shows that you actually care about the topic. People are more likely to help someone that actually wants to learn and displays their desire/efforts to them. The rest of this post is mainly source code but at the very end we see a simple “Thanks” which goes a long way. You don’t have to be a kiss-up when asking questions but expressing some form of gratitude is essential if you want to receive the same attitude towards you. Moreover, the answer to this post seemed very formal, gave a detailed and organized explanation, and even recommended that the user post the logs again if the errors occur once more.

## Conclusion

It's extremely frustrating when we encounter issues within our program that seem impossible to solve. We may spend hours or even days trying to figure out what went wrong but see no progress. This frustration is what often leads to ‘dumb’ questions as we just want to be able to solve our issue and move on from the mess. When posting questions in forums we must learn to ask smart questions, we need to put our feelings and ego’s aside and appreciate the generosity and expertise that is being provided to us for free. Remember, there are no dumb questions! But, there are ‘dumb’ questions.
