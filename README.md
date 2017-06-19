This is a fork of [libmtp][0] from [sourceforge][1].  It contains changes I made to get this to compile on MacOS Sierra (version 10.12.5). See the [original README][2] for more information.

# Setup &amp; Installation (for MacOS)

1.  Install `autoconf`, `libtool`, `libiconv` and `gettext` from [homebrew][3]
     
        brew install autoconf
        brew install libtool
        brew install libiconv
        brew install gettext

2.  Clone and enter this repository
    
        git clone https://github.com/indraniel/libmtp-macos libmtp
        cd libmtp

3.  Create the `configure` file
     
        ./autogen.sh

4.  Run the `configure` script
    
        ./configure --prefix=/path/to/installation/directory

5.  Execute the `Makefile`
    
        make

# Additional Notes

The original git repository at sourceforge can be cloned by running the following command:

    git clone https://git.code.sf.net/p/libmtp/code libmtp-code

# LICENSE

GNU LGPLv2

[0]: http://libmtp.sourceforge.net/
[1]: https://sourceforge.net/
[2]: https://github.com/indraniel/libmtp-macos/blob/master/README.original.txt
[3]: https://brew.sh/
