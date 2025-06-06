Cambridge Data Mining and Machine Learning
==========================================

[![LaTeX Badge][LaTeX Badge]][LaTeX URL]
[![Ubuntu Font Badge][Ubuntu Font Badge]][Ubuntu Font URL]
[![Apache License Badge]][Apache License, Version 2.0]

Latex Sources for the slides for Data Mining and Analysis

- [Course Website](https://dataminingbook.info/)
- [Book PDF](https://dokumen.pub/data-mining-and-machine-learning-fundamental-concepts-and-algorithms-2nbsped-1108473989-9781108473989.html)

Setup
-----

1. Install [Tex Live][LaTeX URL] (version ≥ 2021)

   [For Mac users, please run the following commands as well](https://stackoverflow.com/a/64150928)

   ```console
   brew link --overwrite ghostscript
   ```

2. Download and install [Ubuntu Font][Ubuntu Font URL]. For instructions on how to install a new System font please
   refer to the following links:

    - Linux users shall consult [this thread](https://askubuntu.com/a/191782)
    - Mac users can follow [this Apple support](https://support.apple.com/guide/font-book/install-and-validate-fonts-fntbk1000/mac)

3. Make sure [GNU Make] is installed with

   ```console
   make --version
   ```

   which, when installed, outputs something like this

   ```console
   GNU Make 3.81
   Copyright (C) 2006  Free Software Foundation, Inc.
   This is free software; see the source for copying conditions.
   There is NO warranty; not even for MERCHANTABILITY or FITNESS FOR A
   PARTICULAR PURPOSE.

   This program built for i386-apple-darwin11.3.0
   ```

   `make` should be installed in almost every Linux distribution and Mac user can install via `brew install make`

4. Getting LaTeX source code

   ```console
   git clone git@github.com:QubitPi/cambridge-data-mining-and-machine-learning-slides.git
   cd cambridge-data-mining-and-machine-learning-slides
   ```

5. Compiling slides

   ```console
   make
   ```

   to compile all the chapter slides. We can also run

   ```console
   make ychap<N>.pdf
   ```

   to compile slides for chapter N. For example:

   ```console
   make ychap1.pdf
   ```

   compiles chapter 1 slides only.

> [!NOTE]
> Please be patient as the compilation takes some time <img src="https://github.com/QubitPi/QubitPi/blob/master/img/%E5%BF%83%E6%B5%B7.png?raw=true" width="5%" />

License
-------

The use and distribution terms for [cambridge-data-mining-and-machine-learning-slides]() are covered by the
[Apache License, Version 2.0].

[Apache License Badge]: https://img.shields.io/badge/Apache%202.0-F25910.svg?style=for-the-badge&logo=Apache&logoColor=white
[Apache License, Version 2.0]: https://www.apache.org/licenses/LICENSE-2.0

[GNU Make]: http://uploads.mitechie.com/books/Managing_Projects_with_GNU_Make_Third_Edition.pdf

[LaTeX Badge]: https://img.shields.io/badge/LaTeX-TeX%20Live%E2%89%A52021-008080.svg?style=for-the-badge&logo=latex&logoColor=white
[LaTeX URL]: https://tug.org/texlive/

[Ubuntu Font Badge]: https://img.shields.io/badge/Ubuntu%20Font-E95420.svg?style=for-the-badge&logo=ubuntu&logoColor=white
[Ubuntu Font URL]: https://design.ubuntu.com/font