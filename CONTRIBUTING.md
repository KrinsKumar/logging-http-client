# CONTRIBUTING.md

Firstly, thank you for your interest in contributing to the project.
<br>Please read below for our contributing guidelines.

## Contributions

We welcome contributions from everyone. Contributions to our projects should be made in the form of GitHub 
pull requests. Please see the [GitHub flow][GHF] for further details.

By default, each change in the PR automatically runs all the tests via [GitHub actions][GHA]. If tests are failing, 
make sure to address the failures. Otherwise, you can wait for a review.

If comments have been given in a review, they have to get integrated. For those requested changes, a separate commit 
should be created and pushed to your remote development branch. Don’t forget to add a comment in the PR afterward, so 
everyone gets notified by GitHub. Keep in mind that reviews can span multiple cycles until we are happy with the new code.

## Writing Code

We follow the [PEP 8 – Style Guide for Python Code][PEP8], adhere to the [Test-driven development][TDD] style of programming,
and are a fan of [Robert C. Martin teachings of Clean Code][CC] principles, for the most part. If there is something unclear 
of the style, just look at existing code which might help you to understand it better.

### Commits Checklist

- We follow [Conventional Commits][GCMG] for writing our git messages.
- You can use the following template for your commit message:
    ```
    <type>[optional scope]: <description>

    [optional body]

    [optional footer(s)]
    ```

### Pull Request Checklist

- Create a new branch and, if needed, rebase to the current main
  branch before submitting your pull request. If it doesn't merge cleanly with
  main you may be asked to resolve those conflicts.
- Commits should be as small as possible, while ensuring that each commit is
  correct independently (i.e. each commit should compile and pass tests).
- If your patch is not getting reviewed, or you need a specific person to review it, 
  you can @-reply a reviewer asking for a review in the pull request or a comment.
- Ensure you add tests relevant to the fixed bug or new feature, untested code is undesirable.

For code reviews, we follow [Conventional Comments Format][CCF], which is a standard for formatting 
comments of any kind of review/feedback process.

## Conduct

We follow the [GitHub Community Code of Conduct][GHCCC]. In short, please treat GitHub Community with respect. We are 
a shared resource — a place to share skills, knowledge, and interests through ongoing conversation.

All code in this repository is under The MIT License.

___

[GHF]: https://docs.github.com/en/get-started/quickstart/github-flow
[GHA]: https://github.com/propactive/propactive/actions
[PEP8]: https://peps.python.org/pep-0008/
[TDD]: https://www.agilealliance.org/glossary/tdd
[CC]: https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29
[GHCCC]: https://docs.github.com/en/site-policy/github-terms/github-community-code-of-conduct
[GCMG]: https://www.conventionalcommits.org/en/v1.0.0/#summary
[CCF]: https://conventionalcomments.org/
