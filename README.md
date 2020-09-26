
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0cd20e790e1249cd8bf811e685c16ef6)](https://app.codacy.com/manual/99002605/Linux_OS?utm_source=github.com&utm_medium=referral&utm_content=99002605/Linux_OS&utm_campaign=Badge_Grade_Settings)

![cppcheck-action](https://github.com/99002605/Linux_OS/workflows/cppcheck-action/badge.svg)
name: cppcheck-action
on: [push]

jobs:
  build:
    name: cppcheck
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
        
      - name: Install cppcheck
        run: sudo apt-get -y install cppcheck
      - name: Cppcheck code
        run: cppcheck
