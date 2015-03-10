jscs mirror
===========

Mirror of jscs package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For jshint: see https://github.com/jscs-dev/node-jscs


### Using jscs with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/gisce/pre-commit-jscs
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: jscs
