# Windows Azure Storage Client Library for C++

The Windows Azure Storage Client Library for C++ allows you to build Windows Azure applications 
that take advantage of scalable cloud computing resources. Please note that this library is a CTP (Community
Technology Preview) release.

# Features

- Tables
    - Create/Delete Tables
    - Query/Create/Read/Update/Delete Entities
- Blobs
    - Create/Read/Update/Delete Blobs
- Queues
    - Create/Delete Queues
    - Insert/Peek Queue Messages
    - Advanced Queue Operations

# Getting started

For the best development experience, developers should use the official Microsoft NuGet packages for libraries. NuGet packages are regularly updated with new functionality and hotfixes. 

## Requirements

- Windows Azure Subscription: To call Windows Azure services, you need to first [create an account](https://account.windowsazure.com/Home/Index). Sign up for a free trial or use your MSDN subscriber benefits.

## Need Help?

Be sure to check out the Windows Azure [Developer Forums on MSDN](http://go.microsoft.com/fwlink/?LinkId=234489) if you have trouble with the provided code or use StackOverflow.

## Collaborate & Contribute

We gladly accept community contributions.

- Issues: Please report bugs using the Issues section of GitHub
- Forums: Interact with the development teams on StackOverflow or the Windows Azure Forums
- Source Code Contributions: Please follow the [contribution guidelines for Windows Azure open source](http://windowsazure.github.io/guidelines.html) that details information on onboarding as a contributor 

For general suggestions about Windows Azure please use our [UserVoice forum](http://www.mygreatwindowsazureidea.com/forums/34192-windows-azure-feature-voting).

## Download & Install

### Via Git

To get the source code of the SDK via git just type:

```bash
git clone git://github.com/WindowsAzure/azure-storage-cpp.git
cd azure-storage-cpp
```

### Via NuGet

To get the binaries of this library as distributed by Microsoft, ready for use
within your project you can also have them installed by the package manager [NuGet](http://www.nuget.org/).

`Install-Package wastorage -Pre`

## Code Samples

How-Tos focused around accomplishing specific tasks are available in the [samples folder](Microsoft.WindowsAzure.Storage/samples/).
