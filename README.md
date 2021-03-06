Code reviews!
=============

## Tips

1. Code in any language you want to.

2. You don't need to have the complete solution before you submit a pull
   request. It's better to get feedback as you work through the problem.

3. To make it easier for others to run your code, please include a build script
   and README detailing how to build, run, and test your code.

4. Watch the <https://github.com/CougarCS/code-reviews> repository
   to receive all code reviews for everyone in your e-mail. This way you can
   learn from more people.

5. Have fun!

## Instructions

0. Install git.

   On Unix, Mac OS X, use your package manager.

   On Windows, install [Git Bash](http://git-scm.com/download/win). You can type your git commands in the Git
   Bash shell.

   If you are new to Git, go through the tutorial at <https://try.github.io/>.

   Create a GitHub account.

1. Go to <https://github.com/CougarCS/code-reviews>. Click fork.

2. Clone your fork:
   
	    git clone https://github.com/[YOUR USERNAME]/code-reviews

3. Open up a bash prompt (Git Bash on Windows). Change your directory to the
   cloned repository:

	    cd code-reviews

4a. Run the command:
   
	   ./review.pl

   This will present a menu that will help you make pull requests on separate
   branches for each problem.

4b. If you understand how to branch, you can choose not to use `review.pl`.
    Use the convention of {problem name}/{Github username}.

   For example,

	   # Github username is foo
	   git clone https://github.com/foo/code-reviews
	   cd code-reviews
	   # you must use upstream/master as your start point to have a clean pull request
	   git checkout -b prob01-poker/foo upstream/master
	   # solve problem
	   git push origin prob01-poker/foo

5. Submit a pull request by going to your pull request page or go to

	    <https://github.com/<GITHUB USER>/code-reviews/compare/>

   and compare against the branch for the problem.

