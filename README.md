# pvs-tricks
Set of small tips and tricks for the PVS prover. Please contribute (via PRs) ! Inspired by the coq equivalent (https://github.com/tchajed/coq-tricks)

## Useful links
* The PVS documentation [http://pvs.csl.sri.com/documentation.html](http://pvs.csl.sri.com/documentation.html) that also comes with an installation of PVS: a goto reference. For writing specifications, see the *language* doc. For tactics see the *prover* doc. For general management of projects see *user-guide*.
* The bible for basic tips : [https://shemesh.larc.nasa.gov/PVSClass2012/pvsclass2012/lectures-printer/Survival_Tips.pdf](https://shemesh.larc.nasa.gov/PVSClass2012/pvsclass2012/lectures-printer/Survival_Tips.pdf) - the survival tips. As you go on using PVS you'll probably need all of them at least once

## System
* You can resize the width of the displayed (pretty-printed) formulas by using `M-x eval-expression` and then typing `(pvs-set-linelength n)` where n is the value you want
* When working with long sequents, you might prefer having the `step-proof` setup horizontal rather than vertical. You can bind `C-x |` to switch from the vertical splitting of pvs to an horizontal one by adding the content of `emacs/splitting.el` to your `.emacs`
