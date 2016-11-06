# URL

## zstandard

https://code.facebook.com/posts/1658392934479273/smaller-and-faster-data-compression-with-zstandard/
https://github.com/facebook/zstd
**Not working** https://video-bru2-1.xx.fbcdn.net/v/t43.1792-2/14150783_1386632824683390_2087162222_n.mp4?efg=eyJybHIiOjE1MDAsInJsYSI6NDA5NiwidmVuY29kZV90YWciOiJzdmVfaGQifQ%3D%3D&rl=1500&vabr=222&oh=69fe5fcb4dae443aa0106bdcbf38f3f4&oe=57FFE495
https://arxiv.org/pdf/1606.00519v1.pdf

## FSE

https://fastcompression.blogspot.be/2013/12/finite-state-entropy-new-breed-of.html


# Improvments

* Memory (RAM):
    * zlib -> max 32kB
    * zstd actual limit!
* Parallel execution:
    * multiple instructions for one cycle
        * multiple ALU
        * out-of-order execution
    * multiple cores
* branchless design
* FSE (finite state encoding)
* repcode modeling
* dictionary for small data
