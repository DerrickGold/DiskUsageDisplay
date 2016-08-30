#DiskUsageDisplay

An interactive command line interface for viewing disk space usage.

```
Usage: dui [options] directory

Options:
	-N num	Display only the top 'num' entries for each directory.

	-g 	Display sizes in 1073742824-byte (1-Gbyte) blocks.
	-m 	Display sizes in 1048576-byte (1-Mbyte) blocks.
	-k	Display sizes in 1024-byte (1-Kbyte) blocks.
	-h 	Dislay sizes as "human-readable" numbers, where
		all sizes include a suffix to indicate units of
		bytes or {kilo, mega, giga}bytes.

	-v    Enable verbose/debugging output.
	-c     Enable color.
	-s     Enable static print location.
	-l     Follow directory symbolic links.
	-a 	   Display hidden files.
```