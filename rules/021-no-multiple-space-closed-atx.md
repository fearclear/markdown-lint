---
title: MD021 - Multiple spaces inside hashes on closed atx style header
tags:  [headers, atx_closed, spaces]
alias: no-multiple-space-closed-atx
---

This rule is triggered when more than one space is used to separate the
header text from the hash characters in a closed atx style header:

    #  Header 1  #

    ##  Header 2  ##

To fix this, separate the header text from the hash character by a single
space:

    # Header 1 #

    ## Header 2 ##

Note: this rule will fire if either side of the header contains multiple
spaces.

