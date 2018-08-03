# Starter-kit Repo for the [SBB Train Schedule Optimisation Challenge](https://www.crowdai.org/challenges/train-schedule-optimisation-challenge) on [crowdAI](https://www.crowdai.org)

In this repo you will find background material, sample files and support scripts that help you to get started with the challenge.

## Contents of this Repo
* In the [Documentation](documentation) folder you find detailed explanations of our data models, as well as the business rules that have to be observed when constructing a timetable.
* The [sample_files](sample_files) folder contains some simple sample instances and solution. We use these in the documentation to explain our data models and the grading function.
* The [problem_instances](problem_instances) folder contains the actual timetabling problem instances that you need to solve for this challenge.
* The [utils](utils) folder contains some utilities such as
    - a [script](utils/validate_solution.py) to evaluate _individual_ solutions to problem instances without a "formal" submission. There is also an accompanying [notebook](utils/validate_solution.jpynb) explaining its use.
    - a [script](utils/route_graph.py) that transforms the routes in a problem instance into directed graphs in the [networkx](https://networkx.github.io/) package.