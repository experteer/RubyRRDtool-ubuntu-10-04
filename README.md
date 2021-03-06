RubyRRDtool-ubuntu-10-04
========================

(NOTE: this is a patched clone from the original bindings (http://rubyrrdtool.rubyforge.org/) 
that compiles on Ubuntu 10.04-lts (Fedora 16 is also known to work)

Authors: David Bacher <drbacher at alum.mit.edu>
         Mark Probert <probertm at acm.org>  
based on work by Miles Egan <miles at caddr.com>


== Introduction 

rubyrrdtool provides ruby bindings for RRD functions (via librrd), with
functionality comparable to the native perl bindings. See examples/minmax.rb
or the unit tests in the test directory for scripts that exercise the
rrdtool functions. 


== Installation

rubyrrdtool requires RRDtool version 1.2 or later. Some RRD functions such
as rrddump are only available with the latest RRDtool.

Installation is standard. If you've installed the gem, you should be ready
to go. Otherwise, simply run:

ruby extconf.rb
make
make install

I hope this works for you.  Please let me know if you have any problems or
suggestions.

Thanks to Tobi for rrdtool!


== To do

* Documentation
* Build an interface that feels more ruby-like around this simple functional
  translation


== License

(the MIT license)

Copyright (c) 2006 

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
