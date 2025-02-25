Download Link : https://programming.engineering/product/take-home-quiz-uncertainty-2/

# CSC384-Take-Home-Quiz-Uncertainty
Take-Home Quiz: Uncertainty

Submissions must be a single PDF file named csc384probquiz.pdf, submitted to MarkUs. Submissions must be typed/legible. Please refer to the course information sheet for the late submission policy.

    Bayes’ Burrito Bowls is a food truck that serves burrito bowls (obviously). You can choose:

        a type of rice, which can be; white, brown

        a type of bean, which can be; black, pinto, lima, or kidney

        any of the following toppings; guacamole, corn, salsa, sour cream, onion, lettuce, or cheese

We model each type of burrito as a triple (R, B, T ), where R and B are the types of rice and bean, and

    is any subset of the toppings. The type of burrito a customer picks depends on his/her preferences. We can model such preferences using a probability distribution over (R, B, T ).

        How many different types of burrito bowls are there?

        Eshan builds a burrito bowl as follows: He first chooses the type of rice and bean independently of each other. Based on both these choices, he chooses the toppings (the toppings are not chosen independently of each other). Provide an appropriate factorization of PEshan(R, B, T ) and the number of values that must be known to compute it for any R, B, T .

        Zafeer builds a book as follows: He first chooses type of rice. Based on this choice, he chooses a type of bean. He chooses the toppings independently of the other choices (toppings are not chosen independently of each other). Provide an appropriate factorization of PZafeer(R, B, T ) and the number of values that must be known to compute it for any R, B, T .

Take-Home Quiz on Uncertainty, University of Toronto, CSC384 – Intro to AI, 2

Take-Home Quiz on Uncertainty, University of Toronto, CSC384 – Intro to AI, 3
	

        			

        P(M = train)
        		
        				

        0.6
        		
        				

        M
        	

        N

        M
        	

        N
        	

        P(T = early|M, N)
        			

        train
        	

        0
        	

        0.9
        					

        train
        	

        1
        	

        0.85
        					
        				

        T
        	

        S

        train
        	

        2
        	

        0.60
        	

        car
        	

        0
        	

        0.75
        					

        car
        	

        1
        	

        0.75
        					

        car
        	

        2
        	

        0.75
        				

        F

