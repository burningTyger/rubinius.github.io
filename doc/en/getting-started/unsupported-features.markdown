---
layout: doc_en
title: Unsupported Features
previous: Troubleshooting
previous_url: getting-started/troubleshooting
next: Contributing
next_url: contributing
---

While Rubinius aims to support as many features of the Ruby language as
possible there are certain ones that might not be implemented.

### Unsupported Libraries

* Continuation
* Ripper
* TracePoint
* Tracer

### Unsupported Features

* Refinements (introduced in Ruby 2.0/2.1)
* $SAFE levels
* Kernel.trace\_var
* Kernel.set\_trace\_func

### In Progress

The following features are currently a work in progress and will be available
in the future:

* Keyword arguments: <https://github.com/rubinius/rubinius/issues/2669>
