# Challenges in Serverless
* Smaller deployment units
* Difficult to contain blast radius
* Managed Services create more unknown unknowns and have their own failures
* Managed Services don't lead to good fallbacks
* Increased and more complex dependencies

# Areas that are testable
* Latency Injection
** Don't forget about cold start issues
** Don't forget timeout issues
* Error Injection
** 500s
** DynamoDB provioned throughput exceeded

Steps
1. Define steady state
2. Establish Hypothesis
3. Run Experiment
4. Disprove / Prove Hypothesis
