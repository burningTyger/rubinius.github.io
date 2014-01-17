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
* TracePoint
* Tracer

The following will not be implemented in the foreseeable future:

**Ripper**: Ripper is a parser library that exposes the guts of the MRI parser.
The API is anything but well designed and its output is inconsistent and often
downright confusing. It is recommended to use
<https://github.com/whitequark/parser> or
<https://github.com/seattlerb/ruby_parser> instead if one needs a Ruby parser
that is not tied to a particular Ruby implementation.

### Unsupported Features

* Kernel.trace\_var
* Kernel.set\_trace\_func

The following will not be implemented in the foreseeable future:

* Refinements (introduced in Ruby 2.0/2.1)
* $SAFE levels

### In Progress

The following features are currently a work in progress and will be available
in the future:

* Keyword arguments: <https://github.com/rubinius/rubinius/issues/2669>
