# WindBorne Machine Learning Research Engineer — Application Challenge

## 1. Which of our open ML Research Engineer roles are you interested in, in order?

General > Applied Research > Model Evaluation. My PhD work moves between scientific ML, physical forecasting, data assimilation, inverse problems, and numerical experiments, so I am most excited by a role where I can follow the most important technical problem rather than stay inside one modeling niche.

## 2. Describe an ML idea you were initially excited about but later decided was wrong or unimportant. What changed your mind?

I was excited by multi-route flow-map control for full-waveform inversion: alternative paths should agree, so I expected consistency to guide optimization into better basins. Controlled tests changed my mind. It reduced route disagreement but not the recovered-model error, and the control could trade off against the unknown itself. I stopped treating consistency as the main mechanism.

## 3. Describe a time when you embarked on a sidequest / took initiative outside your core job responsibilities. What value did you add to your organization? What drove you to action?

While building a GNN for river forecasting, I worried that better test error might just come from graph smoothing. Outside the core ML pipeline, I built a 1D shallow-water solver with MUSCL, HLL, RK2, and forward/reverse tests. That sidequest exposed the directionality failure, gave us a physical diagnostic, and directly shaped the refinement method that became an ICDM 2026 paper.

## 4. How could better accuracy fail to translate into more useful forecasts for a weather model?

Lower global RMSE can make a weather forecast less useful if the gain comes from smoothing toward common conditions. Users care about timing, calibration, spatial localization, and rare high-impact events. A model can improve average error while weakening hurricane intensity, frontal timing, or flood-producing extremes—the cases where forecast value is highest.

## 5. Describe a time you changed how you use LLMs in your work — switching models, tools, or workflows. What did you observe that prompted the change?

I stopped using LLMs for one-shot code generation after plausible implementations made weak inverse-problem ideas look convincing. Now I use them to propose the smallest test, write instrumentation, and generate competing hypotheses; then I run multi-seed or controlled experiments before expanding the idea. The workflow became slower per prompt but much faster at killing bad directions.
