# C++ for Games Learning Portfolio

A Github Pages template for academic websites. This was forked from [Academic Pages](https://github.com/academicpages/academicpages.github.io) which was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See [LICENSE](LICENSE).

I think I've got things running smoothly and fixed some major bugs, but feel free to file issues or make pull requests if you want to improve the generic template / theme.

> Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file.

## Instructions

1. Register a GitHub account if you don't have one and confirm your e-mail (required!).
2. Go to this repository [this repository](https://github.com/BredaUniversityGames/cppforgames.github.io) and create a new GitHub repository by clicking the "Use this template" button in the top-right.
3. Name the new repository `[your GitHub username].github.io`.
4. Edit the `_config.yml` file to set site-wide configuration and create content & metadata.
5. Upload any files (like PDFs, .zip files, etc.) to the `files/` directory. They will appear at `https://[your GitHub username].github.io/files/example.pdf`.
6. Commit and push any changes to your repository.
7. Open your browser and navigate to `https://[your GitHub username].github.io/`. You should see your new website!

See more info at <https://academicpages.github.io/>

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and make updates as detailed above
1. Make sure you have Ruby, and Node.js installed:
   1. [Ruby](https://www.ruby-lang.org). For Windows install [RubyInstaller](https://rubyinstaller.org/). Make sure you download the latest `Ruby+Devkit` installer.
   2. [Node.js](https://nodejs.org). Download and install the latest LTS release.
   3. After installing, open a command terminal and run the command `ruby -v` to check if Ruby is correctly installed, `bundler -v` for Bundler and and `node -v` for Node.js.
1. Use `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `jekyll serve --livereload` to generate the HTML and serve it from <http://localhost:4000> the local server will automatically rebuild and refresh the pages on change.

## Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch.

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.
