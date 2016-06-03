# Phonebook

An phonebook program to illustrate the impact of cache miss

## Summary

- This project derived from the homework of [NCTU embedded system course](http://wiki.csie.ncku.edu.tw/embedded/2016q1h1).
- The objects of it are to realize the software optimization, and familiar with the performance analysis tool.
- Although it used some Linux-only functions and tools, such as perf, I try to do these tasks with alternative tools and ways on OS X enviroment.

### Requirment
- Reduce the time cost of `findName()`
- Clear the cache before executing phonebook_orig and phonebook_opt 
- Use [astyle](http://astyle.sourceforge.net/astyle.html) to format your code
`astyle --style=kr --indent=spaces=4 --indent-switches`

### Optional
- Reduce the time cost of `append()` as well
- Support fuzzy search

## Licensing
`phonebook` is freely redistributable under the two-clause BSD License.
Use of this source code is governed by a BSD-style license that can be found
in the `LICENSE` file.
