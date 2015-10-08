## Tag-Release Cycle

1. update docs
2. update version strings
  1. docs/conf.py
  2. setup.py
3. run PEP8 check
4. build and run function checks on 3 platforms
5. update release notes
6. tag latest commit
7. build RTD docs
8. build distributions for Python 3.3, 3.4, 3.5
  * linux - sdist
  * osx - build and modify wheels to work on all versions
  * windows - build 32-bit
9. push to PyPI