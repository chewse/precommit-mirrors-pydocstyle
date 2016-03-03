Pydocstyle mirror
=============

Mirror of the pydocstyle (formerly pep257) package for pre-commit.

For pre-commit see: https://github.com/pre-commit/pre-commit

For Pydocstyle see: https://github.com/PyCQA/pydocstyle


### Using Pydocstyle with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/chewse/pre-commit-mirrors-pydocstyle
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: pydocstyle
