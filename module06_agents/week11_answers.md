# Week 11 answers

## Exercise 1
1. The message the customer never saw: You are sunny. answer in one short sentence. AKA the system message. 
2. How many times the customer has spoken: Two times.
3. Can the model tell that the last reply came from the order tool? Why does that matter?: No it can't. This is because every reply in the history has a role assistant,The model reads the whole regardless of if a rule, tool or model wrote it. It reads the entirity of the history, which allows it to copy the pattern of a previous answer in order to respond with something unprecedented. 
4. The customer now types "thanks". How many messages are sent on the next call?: It'll send 6 total messages. The messages in the messages list and the new message from the user. 

Exercise 4 Answer: The response I received was 'The store now closes at 11 pm.'. It gave me this answer because the model tried to following allow with the last thing that I had said. A reply like this could cost the shop a loss in trust from their customers. I'd say that facts that can have consequences, like prices or order status should never come from the model. 