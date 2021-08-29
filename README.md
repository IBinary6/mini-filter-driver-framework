# mini-filter-driver-framework
A mini filter driver development framework allows you to develop minit filter driver with different features.

## Windows File System Filter Driver
A file system filter driver intercepts requests targeted at a file system or another file system filter driver. By intercepting the request before it reaches its intended target, the filter driver can extend or replace functionality provided by the original target of the request. File system filtering services are available through the filter manager in Windows. The Filter Manager provides a framework for developing File Systems and File System Filter Drivers without having to manage all the complexities of file I/O. The Filter Manager simplifies the development of third-party filter drivers and solves many of the problems with the existing legacy filter driver model, such as the ability to control load order through an assigned altitude. A filter driver developed to the Filter Manager model is called a minifilter. Every minifilter driver has an assigned altitude, which is a unique identifier that determines where the minifilter is loaded relative to other minifilters in the I/O stack. Altitudes are allocated and managed by Microsoft.

![Filter Model](https://www.easefilter.com/images/filter-manager-architecture.gif)

Even to an experienced developer, developing file system filter driver is certainly a challenge. To develop the filter driver, you can use the WDK, a software toolset from Microsoft that enables the development of device drivers for the Microsoft Windows platform. It includes documentation, samples, build environments, and tools for driver developers. To simplify your development and to provide you with a robust and well-tested file system filter driver that works with all versions and patch releases of the Windows operating systems supported by Microsoft, EaseFilter filter driver SDK will be your best choice, it provides a complete, modular environment for building active file system filters in your application.

## EaseFilter Mini Filter Driver Framework
One might think that writing a file system filter would be a much easier task, since there are lots of starter samples available on internet, but the truth is to write a professional commercial file system filters in the real world is very hard.Sometime writing a file system filter driver is harder than a file system. EaseFilter Mini Filter Driver Framework can provide you a complete, modular environment for building active file system filter driver in your application. 

## What Can You Do With EaseFilter Mini Filter Driver Framework

