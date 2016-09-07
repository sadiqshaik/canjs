@page guides/todomvc TodoMVC
@parent guides


This guide walks through building a slightly modified version of TodoMVC with CanJS's [can-core libraries]
and [can-fixture].


## Setup

The easiest way to get started is to clone this JSBin.  The JSBin starts
with the static HTML and CSS a designer might turn over to a JS developer.

The JSBin also loads [can.all.js], which is a script that includes
CanJS all of CanJS core, ecosystem, legacy and infrastructure libraries.

Generally speaking, you should not use the global can script and instead
should import things directly.

## Create and render the template