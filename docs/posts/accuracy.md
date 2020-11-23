hello.

1.  recap of your model(s) and your predictions. 

-polls, ave 30 days + prev vote = current vote, use reg coefficients + standard error to predict 2020
-prediction map

2. A description of the accuracy of the model(s), including any apparent patterns in the accuracy.  Graphics should be used here.

-50/51 states correct!
-however, state-level pop vote not very accurate
  -mean difference, min + max
  -bias away from trump in certain state? qual description of states
-state-level margins of error: x states w/ zero inside margin, only 1 state flipped
  -why this is important: determining % chance of winning in a state (need more than point prediction)
  -model was underconfident
  -model got lucky
  -margins were not correctly calibrated b/c of small sample size, inclusion of prev vote -- if you're going to rely on polls, particularly on a more granular level, you need to address poll-specific sources of error, correlated errors, where they lead to lots of uncertainty and where they are telling a consistent story

3. Proposed hypotheses for why the model(s) were inaccurate in the estimates or locations where it was inaccurate.  These reasons should not simply be statements of about the quality of the components of the model, e.g., “the polls were not good” or “economic growth was not a good predictor” but should instead be grounded hypotheses on why components of the model may not have been predictive or may not have been predictive in certain cases.
-Model is overly confident in safe states, underconfident in swing states
-makes sense b/c # of polls is not taken into account in aggregation method. few polls in safe states, lots of polls in swing states

4. Proposed quantitative tests that could test these hypotheses, e.g., what data, if available, could allow you to test whether the reason proposed really did cause the inaccuracy in your model.  If there is no plausible test of the hypothesis, explain why.  You do not need to perform these tests or explain them in great detail (e.g., there is no need to write down an equation showing your exact test), just propose them.
-confidence (z score) vs margin of victory
-graphs: confidence vs. margin, poll # as size

5. A description of how you might change your model if you were to do it again. 
-MRP in swing states

