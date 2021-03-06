# The Terminator
This tool is used for killing processes by name and renaming or deleting files that have been locked by that process. I originally created this tool as a way to delete a file that was locked by the explorer.exe process even after a reboot. Finding it useful on occasion, I later decided to expand the features of the program and make it more usable for others. If you launch the program directly, it will load a text-based user interface. In addition to this, you can run it via the command line by passing different arguments to the program, which is useful for running the program as part of a script or batch job.

![Program Screenshot](https://github.com/StevenJDH/The-Terminator/raw/master/terminator-ss.jpg "Screenshot")

Releases: [https://github.com/StevenJDH/The-Terminator/releases](https://github.com/StevenJDH/The-Terminator/releases)

Changelog: [https://github.com/StevenJDH/The-Terminator/wiki/Changelog](https://github.com/StevenJDH/The-Terminator/wiki/Changelog)

## Features
* Kill running processes by name
* Rename or delete a file immediately after killing a process
* Text-based user interface and command line access
* Support for console colors, which could later become a customizable feature
* Support for 32/64-bit Windows systems

## Command line usage
Below is the usage information that is needed to run the program via the command line. The order in which you specify the options does not matter, just make sure that all the needed information is provided.

    Usage: TheTerminator.exe -? | -k <process_name> [-r <old_filename> -n <new_filename> | -d <filename>]

    Options:
      -k, -K         Kills running process by name.
      -r, -R         Use with -k plus it renames a file.
      -n, -N         Use with -r to specify new filename.
      -d, -D         Use with -k plus it deletes a file.
      -?, -h, -H     Displays this usage information.

## GCC compiler support
The project was created using Orwell's fork of Dev-C++ v5.11 running TDM-GCC v4.9.2 with 32/64-bit support. See Orwell's blog http://orwelldevcpp.blogspot.com for more information and download links. If you compile the code without using the provided project files, you may need to add the compiler option -std=gnu11 to add support for raw strings as this is what I used for the graphics, which is a GNU extension. As of GCC 5, that compiler option is on by default. In my brief testing, I successfully compiled the source file with the latest versions of TDM-GCC and MinGW-w64, and while Cygwin64 does compile, it has issues with the console color and the Windows-specific commands, but this was expected. 

## Do you have any questions?
Many commonly asked questions are answered in the FAQ:
[https://github.com/StevenJDH/The-Terminator/wiki/FAQ](https://github.com/StevenJDH/The-Terminator/wiki/FAQ)

## Need to contact me?
I can be reached here directly at [https://21.co/stevenjdh](https://21.co/stevenjdh "Contact Page")

## Want to show your support?

|Method       | Address                                                                                                    |
|------------:|:-----------------------------------------------------------------------------------------------------------|
|PayPal:      | [https://www.paypal.me/stevenjdh](https://www.paypal.me/stevenjdh "Steven's Paypal Page")                  |
|Bitcoin:     | 3GyeQvN6imXEHVcdwrZwKHLZNGdnXeDfw2                                                                         |
|Litecoin:    | MAJtR4ccdyUQtiiBpg9PwF2AZ6Xbk5ioLm                                                                         |
|Ethereum:    | 0xa62b53c1d49f9C481e20E5675fbffDab2Fcda82E                                                                 |
|Dash:        | Xw5bDL93fFNHe9FAGHV4hjoGfDpfwsqAAj                                                                         |
|Zcash:       | t1a2Kr3jFv8WksgPBcMZFwiYM8Hn5QCMAs5                                                                        |
|PIVX:        | DQq2qeny1TveZDcZFWwQVGdKchFGtzeieU                                                                         |
|Ripple:      | rLHzPsX6oXkzU2qL12kHCH8G8cnZv1rBJh<br />Destination Tag: 2357564055                                        |
|Monero:      | 4GdoN7NCTi8a5gZug7PrwZNKjvHFmKeV11L6pNJPgj5QNEHsN6eeX3D<br />&#8618;aAQFwZ1ufD4LYCZKArktt113W7QjWvQ7CWDXrwM8yCGgEdhV3Wt|


// Steven Jenkins De Haro ("StevenJDH" on GitHub)
