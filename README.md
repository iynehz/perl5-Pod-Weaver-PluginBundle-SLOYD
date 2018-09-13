[![Build Status](https://travis-ci.org/stphnlyd/perl5-Pod-Weaver-PluginBundle-SLOYD.svg?branch=master)](https://travis-ci.org/stphnlyd/perl5-Pod-Weaver-PluginBundle-SLOYD)

# NAME

Pod::Weaver::PluginBundle::SLOYD - SLOYD's default Pod::Weaver configuration

# VERSION

version 0.0002

# OVERVIEW

It is nearly equivalent to the following:

```
[@CorePrep]

[-SingleEncoding]
[Name]
[Version]
[Region  / prelude]
[Generic / SYNOPSIS]
[Generic / DESCRIPTION]
[Generic / OVERVIEW]
[Collect / ATTRIBUTES]
command = attr
[Collect / CLASS METHODS]
command = classmethod
[Collect / METHODS]
command = method
[Collect / FUNCTIONS]
command = func
[Leftovers]
[Region  / postlude]
[Authors]
[Legal]

[-Transformer / Lists]
transformer = List
[-Include]
pod_path = lib:bin:docs/pod
insert_errors = 1
```

# AUTHOR

Stephan Loyd <sloyd@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2018 by Stephan Loyd.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
