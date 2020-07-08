RSCODE version 1.3

See the files

```
config.doc 	documentation of some compile time parameters
rs.doc 		overview of the Reed-Solomon coding program
rs.man		a man page, slightly outdated at this point
example.c	a simple example of encoding,decoding, and error correction

Makefile	should work on a Sun system, may require GNU make.


Henry Minsky
hqm@alum.mit.edu
```

Hi. The RSCODE project is an implementation of a Reed-Solomon error correction algorithm. Error correcting codes are marvelous jewels of mathematics and algorithms, providing an almost supernatural ability to recover good data from a corrupted channel.
This implementation of the Reed-Solomon codes provide convenient 'byte-sized' block coding which is convenient for adding protection to data which is stored as eight-bit bytes (i.e., most common computer data).

The Reed-Solomon code is the same one used for encoding of data on Audio CD's and CD-ROM disks, as well as many magnetic and optical disk controllers. You basically want to use Reed-Solomon coding in any situation where "forward error correction" is needed, i.e., the decoder will not have the option of requesting retransmission of bad blocks.

There are many ways you might use error correction coding, such as a high-reliability layer on top of a real-time streaming audio protocol which is implemented atop an unreliable protocol such as UDP. Or else telemetry from a remote data probe, or encoding of data into a photographic image.

The code is licensed under the GPL, however a commercial license is also available. A royalty-free license to modify and redistribute the code in binary or source form is available. [Pricing info is available here](http://beartronics.com/rscode.html). Please contact hqm@alum.mit.edu

Have fun!

Henry Minsky
hqm@alum.mit.edu
Links
Download RSCODE Library Source Code and Other Goodies
Introduction to Reed-Solomon Error Correcting Codes
Example use of the rscode library



```
 * (c) Henry Minsky (hqm@alum.mit.edu) 1991-2009
 *
 * This software library is licensed under terms of the GNU GENERAL
 * PUBLIC LICENSE. (See gpl.txt)
 * 
 * Commercial licensing is available under a separate license, please
 * contact author for details.
 *
 * Source code is available at http://rscode.sourceforge.net
 ```


