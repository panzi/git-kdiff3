# git kdiff3

Use [kdiff3](http://kdiff3.sourceforge.net/) as your diff viewer in [git](http://git-scm.com/).

## Install

Copy `git-kdiff3` somewhere into your `$PATH` or your system git script directory:

	sudo cp git-kdiff3 /usr/libexec/git-core/

## Usage

Compare working copy against `HEAD`:

	git kdiff3
	
Compare working copy against a specific commit/branch:

	git kdiff3 $branch

Compare two commits:

	git kdiff3 $commit1 $commit2
