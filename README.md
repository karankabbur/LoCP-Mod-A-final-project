# LoCP-Mod-A-final-project
Final exam project of the course Lab of computational physics

Monte Carlo simulations and Metropolis algorithm are useful tools to
solve problems in statistical physics where thermodynamic expectation
values of some observables are of interest. In this project we apply
this method to study the 2D Ising model since it has an analytic result
which we can compare with our numerical solution in order to evaluate
the strenght of the algorithm and the quality of this numerical approach
which can be extended to similar model which cannot any loger be treated
analitically. Our study of Ising model using computer simulations
consists of:

-   Simulating the 2D Ising model with lattice size, L = 2, 4, 8, 16 and
    32 and then collecting the data i.e. observables such as Average
    Energy per spin <E>, Magnetisation per spin <M> and Absolute
    magnetization per spin\<\|M\|\>, Susceptibility per spin $\\chi$ and
    Heat capacity per spin C. The data of these observables for each of
    the lattice sizes were stored in text files and recalled later.
-   Plotting the graphs for each of the observables versus temperature
    and studying their nature and behaviour at each of the lattice sizes
    as well as their divergence at critical temperature, $T_c$.
-   Visualization of the Ising model using Opencv software was done
    where in we saw how the 32x32 lattice looked like at different
    temperatures and with the corresponding magnetization curve plotted
    beside it, we were able to appreciate it even better.
-   Finite size scaling concept was introduced and critical exponents
    $\\alpha$,$\\beta$ and $\\gamma$ were calculated with simulation
    data using the linear regression tools that we learnt during the
    course. A special mention to finding $\\beta$ is that we also used
    differentiation from numpy module to find the point of inflection of
    the magnetization curve. And thus using those inflection points of
    Magbetization, ln-ln plot was done and again using regression
    $\\beta$ was obtained.
-   The concept of Finite scaling was extended to include reduced plot
    where the data of various observables and different lattice sizes
    collapsed to the same curve which thus validated the correctness of
    the theretical found critical exponents.
-   Comparison of cold start and hot start of the Ising model simualtion
    was done and studied.
-   The probability distribution of the order parameter was studied
    through plots wherein we obtained Bimodal distribution graph and
    it's behaviour with respect to change in lattice size and also with
    tempertures less than Tc, near Tc and greater than Tc were studied.
-   The correlation time for different temperatures are estimated.


### Authors: Karan Kabbur Hanumanthappa Manjunatha, Angelica Foroni, Campano Dani
