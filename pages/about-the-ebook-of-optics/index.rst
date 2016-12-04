.. title: About the eBook of Optics
.. slug: about-the-ebook-of-optics
.. date: 2016-11-13 09:42:31 UTC+01:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

Hello there! My name is `Kyle M. Douglass`_ and I created this site to
educate others about optics, the science and art of light.

Why would I be so interested in such a technical and academic topic
that I would write a blog about it? There are actually two reasons:

1. Optics, despite being one of the oldest fields of science, is
   practically everywhere in today's high-tech society. From the
   miniscule camera on your smart phone to the expansive fiber optic
   networks that power the internet, optics enables an enormous amount
   of the technology that we take for granted. Even a basic
   understanding of light goes a long way towards knowing how today's
   modern societies work.
2. The teaching of optics has, in my opinion, been slow to adapt to
   the information age. Optics text books still spend page after page
   deriving equations in the expectation that students will magically
   distill the important concepts themselves. During my studies which
   began in the early 2000's, I watched as my engineering and computer
   science colleagues benefited from new teaching styles that
   incorporated interactive and code-based examples into the
   classroom. These new tools for teaching are a great idea; why not
   incorporate them into the optics curriculum?

.. _`Kyle M. Douglass`: http://kmdouglass.github.io

Code-based Learning
===================

Computer programming is a skill that every modern scientist and
engineer should have, from electrical engineers to biologists and
psychologists. In this blog you will find that I make heavy use of
code examples. Nearly all of this code is written in `Python`_, a very
easy to learn and powerful programming language used by both amateurs
and professionals across the globe. You can download and run each
computational blog post yourself to conduct your own numerical
experiments in optics.

The easiest way to get Python and its scientific libraries is to use a
package manager like Anaconda. Simply go to `Anaconda's downloads
page`_ and download the installer **for Python 3 or greater**. After
installing Anaconda, download the Anaconda environment file `ebo.yml`_
that I use for this blog. Install the environment by opening the
Anaconda Prompt (on Windows) or a terminal window (on Linux and Mac)
and typing::

  conda env create -f ebo.yml

*Note that you will need to navigate to the directory that contains
the file ebo.yml.* Every time you want to run the code examples,
activate the environment by typing::

  activate ebo

on Windows or::

  source activate ebo

on Linux/Mac. Finally, the individual posts may be downloaded from
this site's `GitHub repository`_. The posts are written in interactive
`Jupyter notebooks`_. If you installed my Anaconda environment, then
you already have the Jupyter notebook server installed. To start
Jupyter, activate the *ebo* environment as described above, navigate
to the folder where you downloaded the notebooks, and type::

  jupyter notebook

A browser window should pop-up in which you can select the notebook
you wish to run. *`Click here`_ for a tutorial on using Jupyter
notebooks.*

.. _Python: https://www.python.org/
.. _Anaconda's downloads page: https://www.continuum.io/downloads
.. _ebo.yml: https://github.com/kmdouglass/ebo/blob/master/files/ebo.yml
.. _GitHub repository: https://github.com/kmdouglass/ebo/
.. _Jupyter notebooks: http://jupyter.org/
.. _Click here: https://www.youtube.com/watch?v=HW29067qVWk

Feedback
========

I am not immune to making mistakes :) If you find an error or bug in
these posts, please e-mail me at kyle.m.douglass_at_gmail.com
(replacing the _at_ with a @ symbol) and clearly state what the error
is and in which page it is located. I and the other readers would
greatly appreciate it. You can also add to the discussion in the
comments section below each post.

Likewise, if you have any ideas for a post, I would love to hear about
them!

Acknowledgments
===============

There are many people and software packages to thank. In particular,
there is

1. **My teachers and professors** for all of their patience and
   encouragement.
2. `Nikola`_ A static site generator written in Python.
3. `Python`_ A wonderful, easy-to-use, yet powerful programming
   language.
4. `Jupyter`_ Sharing ideas and code has never been easier.
5. `Anaconda`_ Essential for managing the many different
   scientific libraries available in Python.

.. _`Nikola`: https://getnikola.com/
.. _`Jupyter`: http://jupyter.org/
.. _`Anaconda`: https://www.continuum.io/anaconda-overview
