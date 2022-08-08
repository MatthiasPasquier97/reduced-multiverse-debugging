# reduced-multiverse-debugging
This is the additional material for the article "Practical Multiverse Debugging through User-defined Reductions" submitted to Models 2022.

It includes the complete Lean formalization of our debugger semantics under “reduced-multiverse-debugging_less_types.lean”.

It also includes the two models presented in the article, ready to be launched in the AnimUML environment. To use them, simply open the html files in a browser.
- The Bakery.html file is the mutual exclusion algorithm example.
- The GenericEnv.html file presents the example of Figure 6.
- The Bakery_OngoingSession.html presents the same Bakery exemple, but with some debug steps already taken (as shown in Figure 5).

To show the history as a branching execution trace, change the setting “Select interaction” to that option at the top of the history (right-hand side) section. 
You can inspect the different breakpoints and reduction functions in "analysis tools -> Watch expression" (in the left-hand side menu).
You can select a reduction and launch run_to_breakpoint in "analysis tools -> In-browser analysis".
