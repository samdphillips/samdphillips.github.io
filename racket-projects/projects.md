# Summary
Here is the current status of Racket packages that I intend to publish and contributions to existing packages that are pending or have pull requests outstanding.  Any packages not listed are not currently active.

# Original Work
# boato
### Status
|  |  |
| - | - |
| **GH Repo Address / Source code**: | `~/projects/racket-dev/boato` |
| **Development Status**: | Pre-alpha |
| **Has LICENSE**: | No |
| **Has README.md**: | No |
| **Has Scribble**: | No |
| **Has Test Suite**: | No |

### Summary
`boato` is an AWS API library package.  Similar to the Python package `botocore` or the Rust `rusoto` package it uses a protocol definition in JSON to generate code.

### Todo

## bubble-babble
### Status
|  |  |
| - | - |
| **GH Repo Address / Source code**: |  `~/projects/racket-dev/bubble-babble` |
| **Development Status**: | Pre-alpha |
| **Has LICENSE**: | No |
| **Has README.md**: | No |
| **Has Scribble**: | No |
| **Has Test Suite**: | No |

### Summary
Implementation of the [bubble-babble](http://bohwaz.net/archives/web/Bubble_Babble.html) algorithm.

### Todo

## creature
### Status
|  |  |
| - | - |
| **GH Repo Address / Source code**: | `~/projects/racket-dev/bubble-babble` |
| **Development Status**: | Pre-alpha |
| **Has LICENSE**: |  No |
| **Has README.md**: | No |
| **Has Scribble**: | No |
| **Has Test Suite**: | No |

### Summary
Ideas for orchestrating programs across several remote hosts.  Has partial libssh binding.  Also has a hostglob implementation.

### Todo
- [ ] integrate partial libssh binding with more complete libssh binding
- [ ] split out hostglob into it's own package

## stream-xml
### Status
| | |
|-|-|
|**GH Repo Address**:| https://github.com/samdphillips/racket-stream-xml |
|**Publishing package**:| Yes |
|**Has LICENSE**:| No |
|**Has README.md**:| No |
|**Has Scribble**:| No |
|**Has Test Suite**: | Partial |

### Summary
### Todo

## json-stream
### Status
| | |
|-|-|
|**GH Repo Address**:|  |
|**Publishing package**:| Yes |
|**Has LICENSE**:|  |
|**Has README.md**:|  |
|**Has Scribble**:|  |
|**Has Test Suite**: |  |

### Summary
### Todo
- [ ] Publish to github

## xml-compliance
### Status
| | |
|-|-|
|**GH Repo Address**:|  |
|**Publishing package**:| |
|**Has LICENSE**:| |
|**Has README.md**:| |
|**Has Scribble**:| |
|**Has Test Suite**: | |

### Summary
### Todo

## racket-utils
### Status
| | |
|-|-|
|**GH Repo Address**:| https://github.com/samdphillips/racket-utils |
|**Publishing package**:| No |
|**Has LICENSE**:| No |
|**Has README.md**:| No |
|**Has Scribble**:| No |
|**Has Test Suite**: | Partial |

### Summary
Three modules that do different things.  One provides more event constructors.  One attempts to make a log4j style logging system on top of the existing Racket logging system.  The final one provides a thin wrapper over the POSIX strftime function

### Todo
- [ ] Write a README.md
	- [ ] `c:strftime` might be leaking `_tm`
- [ ] Add a LICENSE
- [ ] Check that event code works

## racket-inotify
### Status
| | |
|-|-|
|**GH Repo Address**:|  |
|**Publishing package**:| |
|**Has LICENSE**:| |
|**Has README.md**:| |
|**Has Scribble**:| |
|**Has Test Suite**: | |

### Summary
### Todo

## querytool
### Status
| | |
|-|-|
|**GH Repo Address**:| |
|**Publishing package**:| |
|**Has LICENSE**:| |
|**Has README.md**:| |
|**Has Scribble**:| |
|**Has Test Suite**: | |

### Summary
### Todo
- [ ] There is also an rkt-query project.  What is the relationship to this project?

## codecs
### Status
| | |
|-|-|
|**GH Repo Address**:| https://github.com/samdphillips/codecs |
|**Publishing package**:| Maybe |
|**Has LICENSE**:| |
|**Has README.md**:| minimal README |
|**Has Scribble**:| No |
|**Has Test Suite**: | No |

### Summary
A way to define decoders and encoders into a single type.  Atomic values codecs can be combined using combinators to build bigger codecs.

Without a use-case for this package it may not be worthwhile to publish it.

### Todo
- [ ] Write a better README.md
- [ ] Restructure into a proper package
- [ ] Expand on existing tests with a proper test suite
- [ ] `decode-from-bytes` / `encode-to-bytes` would be nice to have a offset to read/write from.
	- [ ] Should be a `decode-from-bytes!` and `encode-to-bytes!`  since it will mutate an existing bytes.

## basic
### Status
| | |
|-|-|
|**GH Repo Address**:| https://github.com/samdphillips/basic |
|**Publishing package**:| |
|**Has LICENSE**:| |
|**Has README.md**:| |
|**Has Scribble**:| |
|**Has Test Suite**: | |

### Summary
### Todo
- [ ] Restructure into a proper package

# Contributions
## asn1
## gregor / cldr