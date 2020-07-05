# CPC

## About

[CPC](https://github.com/setext/CPC) is a prototype with a comprehensive taxonomy for comments and use program analysis to propagate comments. We evaluate it on 5 projects. The evaluation results demonstrate 41573 new comments can be derived by propagation from other code locations with 88% accuracy. Among them, we can derive precise functional comments for 87 native methods that have neither existing comments nor source code. Leveraging the propagated comments, we detect 37 new bugs in open source large projects, 30 of which have been confirmed and fixed by developers, and 304 defects in existing comments (by looking at inconsistencies between existing and propagated comments), including 12 incomplete comments and 292 wrong comments. Our user study confirms propagated comments align well with existing comments in terms of quality.

Our demo is avaliable at https://github.com/setext/CPC

