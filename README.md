# Building a Robot Judge 2021

This is Federico Mantovani's private fork of the BRJ repository at <https://github.com/elliottash/robot_judge_2021>.

## Git Instructions

These instructions are for the case where you forgot how forks work in git.

The repo has two remotes:

- `origin`: Main remote you should push to
- `upstream`: Main remote you should pull new changes from

To get the newest version of Dr. Ash's repository, execute

```shell
git fetch upstream
git rebase upstream/main # If there are no conflicts
# -- OR --
git merge upstream/main # If there are changes in older files
```

To commit some new solutions to your repository, run the following command:

```shell
git add * # Add whatever you wanna commit
git commit -m "My cool commit"
git push # Push is set up to automatically push to `origin`
# -- OR --
git push origin/main # Manually push to `origin`
```

Remember, there is no more `master` branch, it is now called `main`.

---

**(Main repository README)**

# Building a Robot Judge: Data Science for Decision-Making
**Autumn 2021, ETH Zurich**

Lecture slides (slides), code examples (notebooks), and homework assignments (assignments).

[References and Readings](https://docs.google.com/document/d/14g-hYQq9kExzpo4pEBYd4YKmcG08MoG8IjLlSEGvHCw/edit?usp=sharing)

Thanks to Christoph Goessmann, Malka Guillot, and Claudia Marangon for contributions to these materials.

[Autumn 2020 version](https://github.com/elliottash/robot_judge_2020)