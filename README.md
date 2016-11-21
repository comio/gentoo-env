# gentoo-env

Usage:

Copy the gentoo-env/* files into to /etc/porage/env.

Add the following to /etc/portage/package.env file(s):

package-atom compiler-{gcc,clang} -> to enable GCC or CLANG compiler suites
package-atom {lto,lto-thin}       -> to enable LTO (Link Time Optimization) or CLANG specific "LTO-Thin"
package-atom debug                -> to enable debug stuffs (symbols, ...)

You can also mix the profiles. Example:

package-atom compiler-clang lto   -> enables clang compiler and lto feature.

That's all.

comio
