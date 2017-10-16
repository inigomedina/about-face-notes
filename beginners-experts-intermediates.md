# The problem

It seems impossible to find the right balance catering the needs of the first-timer and the needs of the expert.

One of the eternal conundrums of interaction and interface design is how to address the needs of both beginning users and expert users with a single, coherent interface.

# Perpetual intermediates

Most users are neither beginners nor experts: they are intermediates. The experience level of people performing an activity tends, like most population distributions, to follow the classic statistical bell curve. Skill levels give small number on the extremes and majority in the center.


     Beginners 	       		     Intermediates	       		      Experts

     What does the program do?	     I forgot how to import.		      How do I automate this?
     How do I print?	   	     How do I find X?			      Can this be changed?
     What is the program's	     What was the command for		      How can I customize this?
     scope?  	 		     X?	      	  	  		      Is there a keyboard equivalent?
     Where do I start?		     What new features are in
     	      			     this upgrade?
                             --------------------------------------
                           /                                        \
                         /                                            \
		       /		                                \
		     /                                                    \
    -----------------                                                       ---------------------------------


That bell curve is dynamic in time: the begineers do not remain beginners for very long. Neither the experts.

Learning and improving is rewarding, so beginners become intermediates very quicky, or they drop out altogether.


DESIGN PRINCIPLE: nobody wants to remain a beginner.

REFERENCE: Larry Constantine, his book "Software for Use", referes to the intermediate users as Improving Intermediates. They are also called Perpetual Intermediates.

A well-balanced user interface takes the same approach: it doesn't cater to the begineer or to the expert, but rather devotes the bulk of its efforts to satisfying the perpetual intermediate.

In some specialized products, it is appropriate to optimize the user experience for experts. In particular, tools that technically minded people rely on for a significant portion of their professional responsibilities should be inflected towards a high degree of proficiency. Development tools often fall into this category, as do scientific instrumentation and medical devices. We expect the users of those products to come to the table with the necessary technical knowledge, and to be willing to invest significant time and effort to mastering the application.

## Designing for different experience levels

Developers are more oriented to experts.

Marketing, management, sales, etc. are more oriented to beginners.

It's amazing to think that the majority of real users are typically ignored.

Goal: rapidly and painlessly get beginners into intermediacy, to avoid putting obstacles in the way of those intermediates who want to become experts, and most of all, to keep perpetual intermediates happy as they stay firmly in the middle of the skill spectrum.

So, let's see a good strategy to achieve that.

## What beginners need

The state of beginnerhood is never an objective. So, it is a rite of passage everyone must experience. Good software shortens that passage without bringing attention to it.

DESIGN PRINCIPLE: imagine users as very intelligent but very busy.

Give some instruction, but not very much. Make a rapid and targeted process.

DESIGN PEOPLE: design using cause and effect, since this way people learn better.

Good example: ski instructor. Does he start talking about weather? Or types of snow? Or meteorology? No, since he will lose his students.


## Getting beginners on boarc

A new user must grasp the concepts and scope of the product quicly or he will abandon it.

Standard online help is a poor tool for providing beginner assistance: its primary utility is as reference, and beginners don't need reference information. They need overview information, such as a guided tour.

A separate guide facility, displayed within a dialog box, is a fine means of communicating overview, scope, and purpose. As long as the guide stays focused on beginner issues, it should be adequate for assisting beginners.

Beginners also rely heavily upon menus to learn and execute commands.


## What experts need

Experts are also a vital group because they have a disproportionate influence on less experienced users. When a prospective buyer considers your product, he will trus the expert's opinion more than an intermediate's.

Experst want shortcuts to everything.

Expert users constantly, aggressively seek to learn more and to see more connections between their actions and the product's behavior and representation. Experts appreciate new, powerful features.


## What perpetual intermediates need

Perpetual intermediates need access to tools. They don't need scope and purpose. ToolTips are the perfect perpetual intermediate idiom: they say nothing about scope and purpose, they state function in the briefest idioms, consuming the least amount of video space in the process.

Online help is a perpetual intermediate tool, since they are motivated to dig deeper and learn. They use it by way of index, so that part of help must be very comprehensive.

Perpetual intermediates identify clearly regular functions. And they know that there are more advanced features, although they don't use them. The knowledge that they are there is reassuring to the perpetual intermediate, convincing him that he made the right choice investing in this product. It gives him something to aspire to and dream about.


