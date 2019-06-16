# An Advanced Scheduler for Intervals - Master’s Thesis Presentation

Intervals are a new, higher-level primitive for parallel programming
allowing programmers to directly construct the program schedule. They
were developed at ETH Zürich and are the subject of my master's
thesis.

The intervals implementation in Java uses a work-stealing scheduler
where a worker running out of work tries to steal work from
others. The scope of this thesis is to improve the performance of the
intervals scheduler.

This repository contains the final presentation of my master's thesis.

## Running the LaTeX scripts

```beamer.sh``` creates the slides and ```handout.sh``` creates handouts (1, 2 or 4 slides per page). 
Execute ```clean.sh``` to remove temporary files.

## Required software

* pdfTeX
* [Rubber](https://launchpad.net/rubber)
* [PDFjam](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/firth/software/pdfjam/)

## License

- **[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)**
- Copyright 2010 © <a href="https://github.com/thom" target="_blank">Thomas Weibel</a>.
