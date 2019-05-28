# Compiled PhreeqcRM and IPhreeqc libraries (version 3.5.0)
I have compiled IPhreeqc and PhreeqcRM using Cmake and Visual Studio 2015 on Windows 10. The source of PhreeqcRM comes from [USGS](https://wwwbrr.cr.usgs.gov/projects/GWC_coupled/phreeqc/). On linux, I have used the usual configure, make, make install sequence of commands on my Linux Mint machine.

You will most probably need [Visual C++ Redistributable for VC 2015](https://www.microsoft.com/en-us/download/details.aspx?id=48145) to use the Windows library. The Linux version of the library should work out of the box. There are convenient [Matlab](https://github.com/simulkade/PhreeqcMatlab) and [Julia](https://github.com/simulkade/JPhreeqc.jl) wrappers for these libraries (Python is coming soon). Each wrapper downloads the right library from this repository, depending on your OS.

# Help
Please let me know if you can compile IPhreeqc and PhreeqcRM on mac and upload the libraries to this repository.
