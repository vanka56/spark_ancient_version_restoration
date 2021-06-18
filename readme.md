
The runtime for spark v0.6 were built on Macbook environment using SBT(v0.14). 
Tonnes of the libraries defined in the sbt either became obsolete or the SBT was not able to identify since they were all
in cloud location whose url started with HTTP and SBT does not like it(since it likes only HTTPs).

So these jars were downloaded from alternate cloud locations(using an extensive google search) and made them available for SBT runtime.

Overall this is an massive effort to build a spark runtime using an ancient version of it. Solely done for educational purpose. Ancient version had onl limited files facilatiting to grasp the architecture and mechanism easily.


Please find the runtime in the below google share:

https://drive.google.com/drive/folders/1TgRb7LNtqxEikfCGMng9rgGdV8XyaPXt