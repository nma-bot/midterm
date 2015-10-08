# Midterm
Midterm Project for [Interface Programming 2 course](https://github.com/kcc-nma-art258) at KCC-NMA

Based on what you've learned from [assignments week 2-6](https://github.com/kcc-nma-art258/assignments), create a basic, single page website showcasing all of the components of your framework.

A good example of what I'm looking for:
- [http://getskeleton.com](http://getskeleton.com)

Other examples:
- [http://semantic-ui.com](http://semantic-ui.com)
- [http://getbootstrap.com/css](http://getbootstrap.com/css/)
- [http://foundation.zurb.com/docs/components/kitchen_sink.html](http://foundation.zurb.com/docs/components/kitchen_sink.html)

## Getting Setup

### Fork [kcc-nma-art258/midterm](https://github.com/kcc-nma-art258/midterm)
- [Forking a repository on GitHub](https://help.github.com/articles/fork-a-repo/)
- [Cloning a repository from GitHub Desktop](https://help.github.com/desktop/guides/contributing/cloning-a-repository-from-github-desktop/)
- In GitHub Desktop, create a new branch called `gh-pages`; this will be the branch that you make a **pull request** for to turn in your final assignment
- Open Atom (or your text editor) and add the **midterm** folder to your project tree view by clicking _'File > Add Project Folder...'_ or using the `cmd-shift-o` keyboard shortcut. _(You can also do this by right-clicking in GitHub Desktop on the **midterm** project and selecting **Open in Atom**)_

## Project Guidelines
- Must use your own custom HTML & CSS (no third-party code!)
- Your project should use Sass and be structured following our CSS architecture guidelines
  - You project should include a `styles/` directory and a main `style.scss` file
  - Your project should include a `base/`, `layout/`, and `modules/` directory
- If possible, your site should be built from the same components you are showcasing, ie. it should include the following files
  - `base/_reset.scss`
  - `base/_typography.scss`
  - `base/_variables.scss`
  - `base/_mixins.scss`
  - `base/_functions.scss`
  - `base/_media-queries.scss`
  - `layout/_grid.scss`
  - `modules/_buttons.scss`
  - `modules/_forms.scss`
- Must be hosted on GitHub in a `gh-pages` branch
- When you are ready to submit your code assignment, create a pull request using the `gh-pages` branch:
  - Have 2 other students review your work by mentioning them using the **@username** syntax in your pull request description (not the title!)
  - If your classmates find any issues, make the fixes locally and push the changes to the same remote branch
  - Once your code has been reviewed by 2 classmates and your code is ready to turn in, create a new comment on your pull request with the words `@micjamking: Final Submission`; this will send me a notification that your assignment is ready to be graded.

### Turning in your project
- Create a pull request from your `<username>/midterm:gh-pages` to `kcc-nma-art258/midterm:master`
- The pull request should have the title `NMA Bot - Midterm` (replacing `NMA Bot` with your name) 
- Turn in your project **by 11:59pm, Monday October 26**.
