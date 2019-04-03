# Azure Pipelines Hosted VS2017 image

The following software is installed on machines in the Azure Pipelines **Hosted VS2017** pool.

Components marked with **\*** have been upgraded since the previous version of the image.


## Chocolatey

_Version:_ 0.10.11<br/>
_Environment:_
* PATH: contains location for choco.exe

## Docker

_Version:_ 18.09.3<br/>
_Environment:_
* PATH: contains location of docker.exe

## Docker-compose

_Version:_ 1.23.2<br/>
_Environment:_
* PATH: contains location of docker-compose.exe

## Powershell Core

_Version:_ 6.1.3
<br/>

## Docker images

The following container images have been cached:
* microsoft/aspnet@sha256:958114016f74f4ffc10b7f065ca4f340e0a0c390cb276c3659d5f8af43d388c7
* microsoft/dotnet-framework@sha256:3c3fe0db41aa3500539a9667e0f1c2f6c2cc411bb658502bef8629f01f78b70e
* microsoft/windowsservercore@sha256:05de0a0ac13d3652bd1f2281b8589459ebb611092e3fe4d8f1be91f1f6984266
* microsoft/nanoserver@sha256:2b783310e6c82de737e893abd53ae238ca56b5a96e2861558fb9a111d6691ddb
* microsoft/aspnetcore-build@sha256:9ecc7c5a8a7a11dca5f08c860165646cb30d084606360a3a72b9cbe447241c0c

## Visual Studio 2017 Enterprise

_Version:_ VisualStudio/15.9.7+28307.423<br/>
_Location:_ C:\Program Files (x86)\Microsoft Visual Studio\2017\Enterprise

The following workloads including required and recommended components are installed with Visual Studio 2017:

* Universal Windows Platform development
* .NET desktop development
* Desktop development with C++
* ASP.NET and web development
* Azure development
* Node.js development
* Data storage and processing
* Data science and analytical applications *
* Game development with Unity *
* Linux development with C++ *
* Game development with C++ *
* Mobile development with C++ *
* Office/SharePoint development
* Mobile development with .NET
* .NET Core cross-platform development
* Visual Studio extension development *
* Python development *
* Mobile development with JavaScript *

In addition the following optional components are installed:

* Microsoft.Net.Component.4.6.2.SDK
* Microsoft.Net.Component.4.6.2.TargetingPack
* Microsoft.Net.ComponentGroup.4.6.2.DeveloperTools
* Microsoft.Net.Component.4.7.SDK
* Microsoft.Net.Component.4.7.TargetingPack
* Microsoft.Net.ComponentGroup.4.7.DeveloperTools
* Microsoft.Net.Component.4.7.1.SDK
* Microsoft.Net.Component.4.7.1.TargetingPack
* Microsoft.Net.ComponentGroup.4.7.1.DeveloperTools
* Microsoft.Net.Core.Component.SDK.1x
* Microsoft.NetCore.1x.ComponentGroup.Web
* Microsoft.VisualStudio.Component.Azure.Storage.AzCopy
* Microsoft.VisualStudio.Component.PowerShell.Tools
* Microsoft.VisualStudio.Component.VC.140
* Component.Dotfuscator
* Microsoft.VisualStudio.Component.VC.ATL
* Microsoft.VisualStudio.Component.VC.ATLMFC
* Microsoft.VisualStudio.Component.VC.ClangC2
* Microsoft.VisualStudio.Component.VC.CLI.Support
* Microsoft.VisualStudio.Component.VC.Modules.x86.x64
* Microsoft.VisualStudio.Component.Windows10SDK.10240
* Microsoft.VisualStudio.Component.Windows10SDK.10586
* Microsoft.VisualStudio.Component.Windows10SDK.14393
* Microsoft.VisualStudio.Component.Windows10SDK.15063.Desktop
* Component.Unreal
* Component.Unreal.Android
* Component.Android.SDK23
* Microsoft.VisualStudio.Component.TestTools.WebLoadTest
* Microsoft.VisualStudio.Web.Mvc4.ComponentGroup
* Component.CPython2.x64
* Microsoft.Component.PythonTools.UWP
* Microsoft.Component.VC.Runtime.OSSupport
* Microsoft.VisualStudio.Component.VC.Tools.ARM
* Microsoft.VisualStudio.ComponentGroup.UWP.VC
* Microsoft.VisualStudio.Component.VSSDK
* Microsoft.VisualStudio.Component.LinqToSql
* Microsoft.VisualStudio.Component.TestTools.CodedUITest
* Microsoft.VisualStudio.Component.TestTools.Core
* Microsoft.VisualStudio.Component.TypeScript.2.0
* Microsoft.VisualStudio.Component.TypeScript.2.1
* Microsoft.VisualStudio.Component.TypeScript.2.2
* Microsoft.VisualStudio.Component.VC.Tools.ARM64
* Microsoft.VisualStudio.Component.Windows10SDK.16299.Desktop.arm
* Microsoft.VisualStudio.Component.DslTools
* Microsoft.VisualStudio.Component.Windows81SDK
* Microsoft.VisualStudio.Component.WinXP
* Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Win81
* Microsoft.VisualStudio.ComponentGroup.NativeDesktop.WinXP
* Microsoft.VisualStudio.ComponentGroup.ArchitectureTools.Managed
* Microsoft.Component.Blend.SDK.WPF
* Microsoft.Component.VC.Runtime.UCRTSDK
* Microsoft.VisualStudio.Component.VC.ATL.Spectre
* Microsoft.VisualStudio.Component.VC.ATLMFC.Spectre
* Microsoft.VisualStudio.Component.Windows10SDK.17134
* Microsoft.VisualStudio.Component.Windows10SDK.17763
* Microsoft.VisualStudio.Component.VC.Runtimes.x86.x64.Spectre
* Microsoft.VisualStudio.Component.VC.Runtimes.ARM.Spectre
* Microsoft.VisualStudio.Component.VC.Runtimes.ARM64.Spectre

## SQL Server Data Tools for VS 2017

_Version:_ 15.1.61901.24070<br/>

The following components are installed:

* SQL Server Data Tools
* SQL Server Analysis Services Designer
* SQL Server Integration Services Designer
* SQL Server Reporting Services Designers

## WIX Tools

_Toolset Version:_ 3.11.2318<br/>
_WIX Toolset Studio 2017 Extension Version:_ 0.9.21.62588<br/>
_Environment:_
* WIX: Installation root of WIX

## .NET 4.7.2

_Version:_ 4.7.03062

## Windows Driver Kit

_Version:_ 10.0.17763.0<br/>

## Azure Service Fabric

_SDK Version:_ 3.3.617.9590<br/>
_Runtime Version:_ 6.4.617.9590

## Python (64 bit)

#### Python 3.6.6
_Environment:_
* PATH: contains location of python.exe

#### Python 2.7.14

_Location:_ C:\Python27amd64

## WinAppDriver

_Version:_ 1.1.1809.18001<br/>

## Android SDK Build Tools

#### 28.0.3

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\28.0.3

#### 28.0.2

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\28.0.2

#### 28.0.1

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\28.0.1

#### 28.0.0

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\28.0.0

#### 27.0.3

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\27.0.3

#### 27.0.2

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\27.0.2

#### 27.0.1

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\27.0.1

#### 27.0.0

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\27.0.0

#### 26.0.3

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\26.0.3

#### 26.0.2

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\26.0.2

#### 26.0.1

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\26.0.1

#### 26.0.0

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\26.0.0

#### 25.0.3

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.3

#### 25.0.2

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.2

#### 25.0.1

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.1

#### 25.0.0

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.0

#### 24.0.3

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.3

#### 24.0.2

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.2

#### 24.0.1

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.1

#### 24.0.0

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.0

#### 23.0.3

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.3

#### 23.0.2

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.2

#### 23.0.1

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.1

#### 22.0.1

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\22.0.1

#### 21.1.2

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\21.1.2

#### 20.0.0

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\20.0.0

#### 19.1.0

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\19.1.0


## Android SDK Platforms

#### 9 (API 28)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-28

#### 8.1.0 (API 27)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-27

#### 8.0.0 (API 26)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-26

#### 7.1.1 (API 25)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-25

#### 7.0 (API 24)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-24

#### 6.0 (API 23)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-23

#### 5.1.1 (API 22)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-22

#### 5.0.1 (API 21)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-21

#### 4.4.2 (API 19)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-19


## Azure/AzureRM Powershell modules

#### 2.1.0

This version is installed and is available via Get-Module -ListAvailable

#### 3.8.0

This version is saved but not installed
_Location:_ C:\Modules\azurerm_3.8.0\AzureRM\3.8.0\AzureRM.psd1

#### 4.2.1

This version is saved but not installed
_Location:_ C:\Modules\azurerm_4.2.1\AzureRM\4.2.1\AzureRM.psd1

#### 5.1.1

This version is saved but not installed
_Location:_ C:\Modules\azurerm_5.1.1\AzureRM\5.1.1\AzureRM.psd1

#### 6.7.0

This version is saved but not installed
_Location:_ C:\Modules\azurerm_6.7.0\AzureRM\6.7.0\AzureRM.psd1

> Note: You can use a spacific Azure PowerShel version in Pipeline using [Azure PowerShell](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/deploy/azure-powershell?view=azure-devops) task.

## Az Powershell modules

#### 1.0.0

This version is saved but not installed
_Location:_ C:\Modules\az_1.0.0\Az\1.0.0\Az.psd1

> Note: You can use a spacific Az module version in Pipeline using [Azure PowerShell](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/deploy/azure-powershell?view=azure-devops) task.

## TLS12

_Version:_ 1.2<br/>
_Description:_ .NET has been configured to use TLS 1.2 by default

## Azure CLI

_Version:_ <br/>
_Environment:_
* PATH: contains location of az.cmd

## Azure DevOps Cli extension

_Version:_ azure-devops                       0.3.0

## Python

_Version:_ 2.7.14 (x86)<br/>_Version:_ 3.4.4 (x86)<br/>_Version:_ 3.5.4 (x86)<br/>_Version:_ 3.6.8 (x86)<br/>_Version:_ 3.7.2 (x86)<br/>_Version:_ 2.7.14 (x64)<br/>_Version:_ 3.4.4 (x64)<br/>_Version:_ 3.5.4 (x64)<br/>_Version:_ 3.6.8 (x64)<br/>_Version:_ 3.7.2 (x64)<br/><br/>
> Note: These versions of Python are available through the [Use Python Version](https://go.microsoft.com/fwlink/?linkid=871498) task.

## Git

_Version:_ 2.21.0<br/>
_Environment:_
* PATH: contains location of git.exe

## Git Large File Storage (LFS)

_Version:_ 2.7.1<br/>
_Environment:_
* PATH: contains location of git-lfs.exe
* GIT_LFS_PATH: location of git-lfs.exe

## Go (x64)

#### 1.9.7

_Environment:_
* GOROOT_1_9_X64: root directory of the Go 1.9.7 installation

#### 1.10.8

_Environment:_
* GOROOT_1_10_X64: root directory of the Go 1.10.8 installation

#### 1.11.5

_Environment:_
* PATH: contains the location of go.exe version 1.11.5
* GOROOT: root directory of the Go 1.11.5 installation
* GOROOT_1_11_X64: root directory of the Go 1.11.5 installation


## Boost

#### 

* PATH: contains the location of Boost version 
* BOOST_ROOT: root directory of the Boost version  installation
* BOOST_ROOT_1_69_0: root directory of the Boost version  installation


## PHP (x64)

#### 7.3.1

_Environment:_
* PATH: contains the location of php.exe version 7.3.1
* PHPROOT: root directory of the PHP 7.3.1 installation

## Ruby (x64)

#### 2.4.3p205

_Location:_ C:\hostedtoolcache\windows\Ruby\2.4.3\x64\bin

#### 2.5.0p0

_Environment:_
* Location: C:\hostedtoolcache\windows\Ruby\2.5.0\x64\bin
* PATH: contains the location of ruby.exe version 2.5.0p0

## Subversion

_Version:_ 1.8.17<br/>
_Environment:_
* PATH: contains location of svn.exe

## Google Chrome

_version:_
71.0.3578.98

## Mozilla Firefox

_version:_
64.0.2

## Selenium Web Drivers


#### Chrome Driver

_version:_
2.45

_Environment:_
* ChromeWebDriver: location of chromedriver.exe

#### Gecko Driver

_version:_
0.23.0

_Environment:_
* GeckoWebDriver: location of geckodriver.exe

#### IE Driver

_version:_
3.8.0.0

_Environment:_
* IEWebDriver: location of IEDriverServer.exe


## Node.js

_Version:_ 10.15.2<br/>
_Architecture:_ x64<br/>
_Environment:_
* PATH: contains location of node.exe<br/>
* Gulp [[90m21:46:04[39m] CLI version 2.0.1<br/>
* Grunt grunt-cli v1.3.2<br/>
* Bower 1.8.8<br/>
* Yarn 1.13.0<br/>

> Note: You can install and use another version of Node.js on Microsoft-hosted agent pools using the [Node tool installer](https://docs.microsoft.com/vsts/pipelines/tasks/tool/node-js) task.

## npm

_Version:_ 6.8.0<br/>
_Environment:_
* PATH: contains location of npm.cmd

## Java Development Kit

#### 1.8.0_202

_Environment:_
* JAVA_HOME: location of JDK
* PATH: contains bin folder of JDK

#### 11.0.2

_Location:_ C:\Program Files\Java\zulu-11-azure-jdk_11.29.3-11.0.2-win_x64

## Ant

_Version:_ 1.10.5<br/>
_Environment:_
* PATH: contains location of ant.cmd
* ANT_HOME: location of ant.cmd
* COBERTURA_HOME: location of cobertura-2.1.1.jar

## Maven

_Version:_ 3.6.0<br/>
_Environment:_
* PATH: contains location of mvn.bat
* M2_HOME: Maven installation root

## Gradle

_Version:_ 5.2.1<br/>
_Environment:_
* PATH: contains location of gradle

## Cmake

_Version:_ 3.13.4<br/>
_Environment:_
* PATH: contains location of cmake.exe

## SQL Server Data Tier Application Framework (x64)

_Version:_ 15.0.4200.1<br/>

## .NET Core

The following runtimes and SDKs are installed:

_Environment:_
* PATH: contains location of dotnet.exe

_SDK:_
* 2.2.104 C:\Program Files\dotnet\sdk\2.2.104
* 2.2.103 C:\Program Files\dotnet\sdk\2.2.103
* 2.2.102 C:\Program Files\dotnet\sdk\2.2.102
* 2.2.101 C:\Program Files\dotnet\sdk\2.2.101
* 2.2.100 C:\Program Files\dotnet\sdk\2.2.100
* 2.1.504 C:\Program Files\dotnet\sdk\2.1.504
* 2.1.503 C:\Program Files\dotnet\sdk\2.1.503
* 2.1.502 C:\Program Files\dotnet\sdk\2.1.502
* 2.1.500 C:\Program Files\dotnet\sdk\2.1.500
* 2.1.403 C:\Program Files\dotnet\sdk\2.1.403
* 2.1.402 C:\Program Files\dotnet\sdk\2.1.402
* 2.1.401 C:\Program Files\dotnet\sdk\2.1.401
* 2.1.400 C:\Program Files\dotnet\sdk\2.1.400
* 2.1.4 C:\Program Files\dotnet\sdk\2.1.4
* 2.1.302 C:\Program Files\dotnet\sdk\2.1.302
* 2.1.301 C:\Program Files\dotnet\sdk\2.1.301
* 2.1.300 C:\Program Files\dotnet\sdk\2.1.300
* 2.1.202 C:\Program Files\dotnet\sdk\2.1.202
* 2.1.201 C:\Program Files\dotnet\sdk\2.1.201
* 2.1.200 C:\Program Files\dotnet\sdk\2.1.200
* 2.1.2 C:\Program Files\dotnet\sdk\2.1.2
* 2.1.105 C:\Program Files\dotnet\sdk\2.1.105
* 2.1.104 C:\Program Files\dotnet\sdk\2.1.104
* 2.1.103 C:\Program Files\dotnet\sdk\2.1.103
* 2.1.102 C:\Program Files\dotnet\sdk\2.1.102
* 2.1.101 C:\Program Files\dotnet\sdk\2.1.101
* 2.1.100 C:\Program Files\dotnet\sdk\2.1.100
* 2.0.3 C:\Program Files\dotnet\sdk\2.0.3
* 2.0.0 C:\Program Files\dotnet\sdk\2.0.0
* 1.1.9 C:\Program Files\dotnet\sdk\1.1.9
* 1.1.8 C:\Program Files\dotnet\sdk\1.1.8
* 1.1.7 C:\Program Files\dotnet\sdk\1.1.7
* 1.1.5 C:\Program Files\dotnet\sdk\1.1.5
* 1.1.4 C:\Program Files\dotnet\sdk\1.1.4
* 1.1.12 C:\Program Files\dotnet\sdk\1.1.12
* 1.1.11 C:\Program Files\dotnet\sdk\1.1.11
* 1.1.10 C:\Program Files\dotnet\sdk\1.1.10
* 1.0.4 C:\Program Files\dotnet\sdk\1.0.4
* 1.0.1 C:\Program Files\dotnet\sdk\1.0.1

_Runtime:_
* 2.2.2 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.2.2
* 2.2.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.2.1
* 2.2.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.2.0
* 2.1.8 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.8
* 2.1.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.7
* 2.1.6 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.6
* 2.1.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.5
* 2.1.4 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.4
* 2.1.3 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.3
* 2.1.2 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.2
* 2.1.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.1
* 2.1.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.0
* 2.0.9 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.9
* 2.0.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.7
* 2.0.6 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.6
* 2.0.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.5
* 2.0.3 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.3
* 2.0.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.0
* 1.1.9 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.9
* 1.1.8 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.8
* 1.1.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.7
* 1.1.6 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.6
* 1.1.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.5
* 1.1.4 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.4
* 1.1.2 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.2
* 1.1.11 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.11
* 1.1.10 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.10
* 1.1.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.1
* 1.0.9 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.9
* 1.0.8 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.8
* 1.0.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.7
* 1.0.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.5
* 1.0.4 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.4
* 1.0.14 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.14
* 1.0.13 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.13
* 1.0.12 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.12
* 1.0.11 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.11
* 1.0.10 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.10

## Mysql

_Version:_ 5.7.21.0<br/>
_Environment:_
* PATH: contains location of mysql.exe

## SQLPS

_Version:_ 1.0

## SQLServer PS

_Version:_ 21.1.18080

## MinGW

_Version:_ 8.1.0<br/>
_Environment:_
* PATH: contains location of the MinGW 'bin' directory

## TypeScript

_Version:_ Version 3.3.3333<br/>

## Miniconda

_Version:_ conda 4.5.12<br/>
_Environment:_
* CONDA: contains location of the root of the Miniconda installation

## Azure CosmosDb Emulator

_Version:_ 2.2.1.0<br/>
_Location:_ C:\Program Files\Azure Cosmos DB Emulator\

## 7zip

_Version:_ 19.00<br/>

## Mercurial

_Version:_ <br/>

## jq

_Version:_ jq-1.5<br/>

## Inno Setup

_Version:_ 5.6.1<br/>

## Perl

_Version:_ v5.26.2<br/>

## GitVersion

_Version:_ 4.0.0.0<br/>

## OpenSSL

_Version:_ 1.1.1a at C:\Program Files\Git\usr\bin\openssl.exe<br/>_Version:_ 1.1.1a at C:\Program Files\Git\mingw64\bin\openssl.exe<br/>_Version:_ 1.0.2j at C:\Program Files (x86)\Subversion\bin\openssl.exe<br/>_Version:_ 1.1.0i at C:\Strawberry\c\bin\openssl.exe<br/>_Version:_ 1.1.1 at C:\Program Files\OpenSSL\bin\openssl.exe<br/>

## Cloud Foundry CLI

_Version:_ 6.43.0<br/>

## Vcpkg

_Version:_ 2018.11.23-nohash<br/>
_Environment:_
* PATH: contains location of the vcpkg directory
* VCPKG_ROOT: root directory of the vcpkg installation