Examples
========

.. note:: These examples only render in a Sphinx project with a proper
   configuration of the Ti\ *k*\ z Sphinx extension.

::

  .. tikz:: \draw[->] (0,0) -- (1,1) -- (1,0)
     -- (2,0);
     :libs: arrows


.. tikz::  \draw[->] (0,0) -- (1,1) -- (1,0)
   -- (2,0);
   :libs: arrows

::

  .. tikz:: An Example TikZ Directive with Caption
     :align: left

     \draw[thick,rounded corners=8pt]
     (0,0)--(0,2)--(1,3.25)--(2,2)--(2,0)--(0,2)--(2,2)--(0,0)--(2,0);

.. tikz:: An Example TikZ Directive with Caption
   :align: left

   \draw[thick,rounded corners=8pt]
   (0,0)--(0,2)--(1,3.25)--(2,2)--(2,0)--(0,2)--(2,2)--(0,0)--(2,0);

::

  An example role :tikz:`[thick] \node[blue,draw] (a) {A};
  \node[draw,dotted,right of=a] {B} edge[<-] (a);`


An example role :tikz:`[blue,thick] \node[draw] (a) {A}; \node[draw,dotted,right
of=a] {B} edge[<-] (a);`

Example of a Ti\ *k*\ z picture included from a file:

::

   .. tikz::
      :include: tikz/example.tikz
      :align: right

.. tikz::
   :include: tikz/example.tikz
   :align: right
