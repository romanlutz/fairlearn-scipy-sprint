![Fairlearn logo](https://github.com/fairlearn/fairlearn/blob/main/docs/_static/images/fairlearn_full_color.png)

# Instructions for SciPy sprints July 2021

Welcome to the Fairlearn sprint at SciPy 2021! We're excited to have you!

## Event info

- [sprint info page](https://www.scipy2021.scipy.org/sprints)

## Preparation

1. Get a [GitHub account](https://github.com/)
2. Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
3. Read through the ways to contribute in the [contributor guide](https://fairlearn.org/main/contributor_guide/index.html) to consider how you'd like to contribute.
4. Look at Fairlearn's issues on GitHub, specifically the ones marked ["help wanted"](https://github.com/fairlearn/fairlearn/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22). Within this category we've marked issues with labels
   - ["good first issue"](https://github.com/fairlearn/fairlearn/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22+label%3A%22good+first+issue%22) means issues are a good fit for first time contributors including people with no prior experience with coding or GitHub. This is an excellent way to get started!
   - ["easy"](https://github.com/fairlearn/fairlearn/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22+label%3A%22easy%22+) means the issue is somewhat harder than a "good first issue", but still quite doable if you have prior experience or you're willing to spend a little bit of time.
   - neither of the two above: this means issues haven't been scoped out properly yet or are more difficult and likely won't be doable within a sprint. If you're still interested just let us know and we'll figure out a way!
   Once you find an issue you're interested in comment on the issue with any questions you may have and let us know that you'd like to do it. This helps us avoid duplication and we can help you quicker.
5. Whenever questions come up don't hesitate to reach out (see "Communication channels" below). We're here to help!
6. Clone the Fairlearn repository onto your machine using `git clone https://github.com/fairlearn/fairlearn.git`.
7. Fork the Fairlearn repository (using the "Fork" button on the [Fairlearn repo](https://github.com/fairlearn/fairlearn)), then run `git remote add <your-alias> https://github.com/<your-alias>/fairlearn/git` while replacing `<your-alias>` with your actual alias. To check whether it worked run `git remote -v` and it should show both `origin` pointing to the original fairlearn repo and `<your-alias>` pointing to your fork. Now you can create a new branch and start changing the world!
8. To check your branch run `git status`. Initially it will point to `main` which is the default. Create a new branch for yourself run `git checkout -b <branch-name>`. `git checkout` is your way of switching branches, while `-b` creates a new branch and should only be added the first time you check out a (new) branch. Whenever you are ready to commit your changes run `git add --all` and `git commit --all` or use the version control functionality of your IDE (e.g., Visual Studio Code). To push the changes to your fork run `git push <your-alias>`.
9. Your Python environment: Consider using [miniconda](https://docs.conda.io/en/latest/miniconda.html). If you want to run Fairlearn code examples simply run `pip install -e .` from the repository root. To run tests or to build the documentation you may need to run `pip install -r requirements-dev.txt`.
10. To build the website follow [these instructions](https://fairlearn.org/main/contributor_guide/contributing_documentation.html#contributing-documentation).
11. To create a pull request go to the [Fairlearn repo](https://github.com/fairlearn/fairlearn/pulls) and hit "new pull request". Click "compare across forks" and subsequently configure the "compare" branch to be the one you pushed your changes to. Briefly check the file changes in the resulting view and click "create pull request" when you're confident about your changes. The following view will ask you to add a pull request title and description, and if you created the pull request in response to an issue add `#<issue-number>` for reference.
12. Celebrate! You did great by participating! Hopefully you've enjoyed your experience, but if not please do let us know how we can do better. If you would like to be a part of the Fairlearn community we'd be thrilled to discuss ways for you to get involved! Reach out!

## Communication channels

The Fairlearn community uses [Discord](https://discord.gg/Wnazkc5h44) for communication. Feel free to join and ask questions or meet other participants. There are both voice/video and text channels. All are welcome!

## Twitter

Please take photos and tweet about the event!

- #FairlearnSprint
- #opensource
- @fairlearn
- Twitter handles of organizers (@romanlutz) and others who helped you!

## Additional resources

- [Mentored sprint instructions](https://mentored-sprints.netlify.app/participants/01-index/)
- [Git tutorial](https://github.com/reshamas/git-intro-workshop/blob/master/extra_resources/resource_git_tutorials.md)
