XenCenter
=========

This repository contains the source code for XenCenter.

XenCenter is a Windows-based management tool for XenServer environments
which enables users to manage and monitor XenServer hosts and resource pools, 
and to deploy, monitor, manage and migrate virtual machines.

XenCenter is written mostly in C#.
   
Contributions
-------------

The preferable way to contribute is to submit your patches to the 
xs-devel@lists.xenserver.org mailing list rather than submitting pull requests. 
Please see the CONTRIB file for some general guidelines on submitting changes.

License
-------

This code is licensed under the BSD 2-Clause license. Please see the LICENSE
file for more information.

How to build XenCenter
----------------------

To build XenCenter, you not only need 
 *  the source from xenadmin repository
 
but also some libraries which we do not store in the source tree:
 *  CookComputing.XmlRpcV2.dll
 *  DiscUtils.dll
 *  ICSharpCode.SharpZipLib.dll
 *  Ionic.Zip.dll
 *  log4net.dll
You can find the source code of these libraries (along with some patches) in dotnet-packages repository.
 
You also need NUnit libraries
 *  nunit.framework.dll
 *  Moq.dll
which can be obtained from http://www.nunit.org/
