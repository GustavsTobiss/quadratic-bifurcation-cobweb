# quadratic-bifurcation-cobweb
The python code I wrote to create various diagrams in my paper about symbolic dynamics.
The idea of symbolic dynamics is roughly to translate a complicated dynamical system into the language of easily manipulated symbols.
The interesting plots are the bifurcation and cobweb diagrams, although there is one other dile which illustrates the relation to the cantor set.

Wikipedia is a great place to learn about these things:

      https://en.wikipedia.org/wiki/Symbolic_dynamics
      https://en.wikipedia.org/wiki/Bifurcation_diagram
      https://en.wikipedia.org/wiki/Cobweb_plot
      https://en.wikipedia.org/wiki/Sharkovskii%27s_theorem
      
It's funny to mention that I had a bug in the bifurcation diagram code that made the images both technically incorrect and less visually striking. 
After spending a decent amount of time to fix this bug, I noticed that many of the bifurcations scattered around Wikipedia had the same exact bug. 
I may spend an afternoon cleaning these articles up if I can find the time; however, the code takes a long time to run (~1 hr) if you crank the numbers up to make the images really nice.
Oh, on that note, I don't claim this code to be efficient in any regard. To quote Dr. McCoy from TOS, "I'm a mathematician, Jim, not a computer scientist!"
